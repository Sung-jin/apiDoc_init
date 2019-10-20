# apiDoc_init
* https://github.com/apidoc/apidoc
* apidoc을 이용하여 api document 생성
* 나름 편하게 구조 잡아서 사용할 수 있도록 만든 틀

## Docker
```
# docker build -t apidoc .

# docker run --rm -v $(pwd):/home/node/apidoc apidoc -o output -i apiDoc

# docker run -d --name=nginx -v output:/usr/share/nginx/html -p 80:80 nginx:alpine
```