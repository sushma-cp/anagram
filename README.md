# anagramServer

## Build and run the solution with docker:

```shell script
docker-compose up --build anagramServer
```

## Test:

### Integration tests:

```shell script
docker run --network host -t postman/newman run "https://www.getpostman.com/collections/7f56d87ab98e182e9f9a"
```

### Manual:

```shell script
curl -i -H "Accept: application/json" -H "Content-Type: application/json" -X GET http://localhost/anagrams/cinema/iceman
```
