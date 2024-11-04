#  Golang Web Server

## Routes

| Method | Path | Handler |
| ------ | ---- | ------- |
| GET    | /    | fileServer |
| GET    | /form.html | fileServer |
| GET    | /hello | helloHandler |
| POST   | /form | formHandler |

## Run

1.
```bash
go build
```

2.
```bash
go run main.go
```
