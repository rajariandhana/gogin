# gogin

``` 
go get .
go run .
```

```
curl http://localhost:8080/albums/
```
```
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```
```
curl http://localhost:8080/albums/2
```