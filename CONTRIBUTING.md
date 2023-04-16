# Run docker local

```
docker run -dp 5000:5000 -w /app -v "/YOURPATH:/app" IMAGE_NAME sh -c "flask run --host 0.0.0.0"
```