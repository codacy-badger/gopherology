# gopherology

🔮 Go microservice that computes the numerological Life Path number for a given birthdate.

## Usage

### `/api/path`

#### Request

```bash
curl -X POST https://gopherology.herokuapp.com/api/path \
  -H 'Content-Type: application/json' \
  -d '{"day":29,"month":11,"year":1975}'
```

#### Response

```json
{
  "number": 8,
  "more_info":" https://www.tokenrock.com/numerology/my_life_path/?num=8"
}
```

## Development

```bash
$ export PORT=1324; go run main.go
```
