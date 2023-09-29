# The 3 most popular Rate Limit Methods implemented in GO, Akhil Sharma

- Token Bucket Algorithm
- Per-client rate limiting
- Using tollbooth as middleware

## To Run

- cd into the project directory
- run `go run main.go`
- in another terminal, run

## To call the API once - 
```bash
curl -i http://localhost:8080/ping
```
## To call the API multiple times - 

```bash
for i in {1..6}; do curl http://localhost:8080/ping; done
```
