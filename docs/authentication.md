# Authentication

All API requests must include a valid API key.

## Header

```http
Authorization: Bearer YOUR_API_KEY
```

## Example Request

```bash
curl -X GET https://api.rosloto.net/v1/player \
-H "Authorization: Bearer YOUR_API_KEY"
```
