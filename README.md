# Dockerfile for jq

Example:

```
docker run --rm -v "$(pwd)":/data -w /data inutano/jq jq '.' mydata.json
```

References:

- [jq command manual](http://stedolan.github.io/jq/manual/)
- [Tutorial in Japanese](http://qiita.com/takeshinoda@github/items/2dec7a72930ec1f658af)
