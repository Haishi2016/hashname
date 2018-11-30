# hashname
Map 32-bit hash into unique names. 

## Install

```bash
go get github.com/Haishi2016/hashname
```

## Sample Usages

* Map a 32-bit hash to a 4-part phrase
```go
hashname.GetNameFromHash(0x1B7B081C)
```
returns 
```go
fussy-moore-lose-blueberry
```
* Map a 16-bit hash to a 2-part phrase
```go
hashname.GetNameFromShortHash(0x0A1D)
```
returns 
```
loyal-anderson
```
* Get a random 2-part phrase
```go
hashname.GetRandomName()
```
returns a random phrase such as:
```
outgoing-jenkins
```