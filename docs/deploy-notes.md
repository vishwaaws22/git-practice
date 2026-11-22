# Deployment notes

- Application: image-upload-api
- Port: 9000 (uvicorn), published as 8080 by the proxy
- Max upload size: 5 MiB
- Health check path: /health
- Allowed types: image/jpeg, image/png
