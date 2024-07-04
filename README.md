# Api in go lang

## Cloning the code 
```
git clone https://github.com/shubham1888/goApi
```
## Changing the directory
```
cd goApi
```
## Get the pacages
```
go get .
```
## Running the code
```
go run .
```

## Get Request
```
curl http://localhost:8080/albums
```

## Get single Data
```
curl http://localhost:8080/albums/2
```

## Post a data
```
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```