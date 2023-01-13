# go-restful-api

## Setup

1. Run `go fetch .`
2. Run `go run .`

## Request Examples

### Fetch all Albums

```shell
curl http://localhost:8080/albums
```

### Fetch single Album

```shell
curl http://localhost:8080/albums/1
```

### Create new Album

```shell
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": 4,"title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```