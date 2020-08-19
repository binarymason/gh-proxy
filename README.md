### Testing locally

```
docker build . -t gh-proxy && docker run -e PORT=80 -p 5002:80 --rm gh-proxy
```
