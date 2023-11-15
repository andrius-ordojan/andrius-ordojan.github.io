windows
docker run -d -p 80:80 -v ${PWD}:/usr/share/nginx/html --name my-static-site nginx:alpine

linux
docker run -d -p 80:80 -v $(pwd):/usr/share/nginx/html --name my-static-site nginx:alpine
