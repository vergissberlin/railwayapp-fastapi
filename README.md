# FastAPI for railway.app

![Template Header](./template-header.svg)

Minimal FastAPI app with Uvicorn for Railway.

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/new/template)

## Environment

| Variable | Description |
|----------|-------------|
| `PORT` | Set by Railway |

## Local

```bash
docker build -t railwayapp-fastapi .
docker run --rm -p 8000:8000 -e PORT=8000 railwayapp-fastapi
```

<!-- footer -->
