# API POINTS

## BIODATA

### Menampilkan Biodata User
```
GET: /biodata

response:
[
  {
    "id"              : "",
    "nama"            : "",
    "sosmed"  : ""
  },
  {
    ...
  }
]
```
### Menampilkan Biodata User Berdasarkan ```id```
```
GET: /biodata/[id]

response:
{
  "id"              : "",
  "nama"    : "",
  "sosmed"          : ""
}
```
### Menambahkan Biodata User
```
POST: /biodata

data:
{
  "nama"    : "",
  "sosmed"          : ""
}

response:
true    //if true
false   //if false
```
### Mengubah Biodata User
```
PUT: /biodata

data:
{
  "nama"    : "",
  "sosmed"          : ""
}

response:
true    //if true
false   //if false
```
### Menghapus Biodata User
```
DELETE: /biodata/[id]

response:
true    //if true
false   //if false
```
## ARTICLE
### Menampilkan Seluruh Article
```
GET: /article

response:
[
  {
    "id"        : "",
    "img"       : "",
    "title"     : "",
    "markdown"  : ""
  },
  {
    ...
  }
]
```
### Menampilkan Article Berdasarkan ```id```
```
GET: /article/[id]

response:
{
    "id"        : "",
    "img"       : "",
    "title"     : "",
    "markdown"  : ""
}
```
### Menambahkan Article
```
POST: /article

data:
{
    "img"       : "",
    "title"     : "",
    "markdown"  : ""
}

response:
true    //if true
false   //if false
```
### Mengubah Article
```
PUT: /article

data:
{
    "img"       : "",
    "title"     : "",
    "markdown"  : ""
}

response:
true    //if true
false   //if false
```
### Menghapus Article
```
DELETE: /article

response:
true    //if true
false   //if false
```