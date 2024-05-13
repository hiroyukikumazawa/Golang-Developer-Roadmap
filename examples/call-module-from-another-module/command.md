```bash
go mod init <new/module/path>
go mod edit -replace example.com/greetings=../greetings
go mod tidy
go run .
go help
```