Fetch the content of each specified URL and prints as text.

`http.Get` makes an HTTP request and, if there is no error, returns the result
in the response struct `resp`. The `Body` field of `resp` contains the server 
response as readable stream. 
`ioutil.ReadAll` reads the entire response. 
`Body` should be closed to avoid leaking resources.

Usage:

```
go build -o fetch main.go
./fetch https://gopl.io
```
