<!-- Code generated by gomarkdoc. DO NOT EDIT -->

# storage

```go
import "github.com/Abbas-gheydi/radotp/pkgs/storage"
```

## Index

- [Constants](<#constants>)
- [Variables](<#variables>)
- [func Delete\(username string\) error](<#Delete>)
- [func Get\(username string\) \(password string, err error\)](<#Get>)
- [func GetAdminPassword\(uname string\) \(password string\)](<#GetAdminPassword>)
- [func Initialize\(\)](<#Initialize>)
- [func IsUserExist\(username string\) \(userExist bool\)](<#IsUserExist>)
- [func Set\(username string, secret string\) error](<#Set>)
- [func SetAdminPassword\(password string\)](<#SetAdminPassword>)
- [func ShaGenerator\(password string\) string](<#ShaGenerator>)
- [func Update\(username string, secret string\) error](<#Update>)


## Constants

<a name="User_not_found"></a>

```go
const (
    User_not_found string = "user not found"
)
```

## Variables

<a name="Dsn"></a>

```go
var (
    Dsn string
)
```

<a name="MaxOpenConns"></a>

```go
var (
    MaxOpenConns,
    MaxIdleConns,
    ConnMaxLifetimeInMiuntes int
)
```

<a name="Delete"></a>
## func [Delete](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L53>)

```go
func Delete(username string) error
```



<a name="Get"></a>
## func [Get](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L56>)

```go
func Get(username string) (password string, err error)
```



<a name="GetAdminPassword"></a>
## func [GetAdminPassword](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L67>)

```go
func GetAdminPassword(uname string) (password string)
```



<a name="Initialize"></a>
## func [Initialize](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L39>)

```go
func Initialize()
```



<a name="IsUserExist"></a>
## func [IsUserExist](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L75>)

```go
func IsUserExist(username string) (userExist bool)
```



<a name="Set"></a>
## func [Set](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L47>)

```go
func Set(username string, secret string) error
```



<a name="SetAdminPassword"></a>
## func [SetAdminPassword](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L70>)

```go
func SetAdminPassword(password string)
```



<a name="ShaGenerator"></a>
## func [ShaGenerator](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/encryption.go#L78>)

```go
func ShaGenerator(password string) string
```



<a name="Update"></a>
## func [Update](<https://github.com/Abbas-gheydi/radotp/blob/main/pkgs/storage/storage.go#L50>)

```go
func Update(username string, secret string) error
```



Generated by [gomarkdoc](<https://github.com/princjef/gomarkdoc>)
