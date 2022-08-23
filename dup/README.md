Looks for the adjacent duplicate lines.

`ioutil.ReadFile` reads the entire contents of a named file and `strings.Split` splits 
a string into a slice substrigs.

Usage:

```
go build -o dup main.go
./dup text.txt
```
