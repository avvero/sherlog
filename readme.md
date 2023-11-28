# ELK

## Run
```bash
docker-compose -f docker-compose.yml up
```
## Test

```bash
echo '{"key": "value", "message": "Hello, Logstash!"}' | nc localhost 5001
```