# Практична робота #3
## Збудувати docker image
    docker build . -t roman20003821/node-js-on-docker:1

## Завантажити docker image на docker hub
    docker push roman20003821/node-js-on-docker:1

## Запустити контейнер з обмеженними memory та cpu
    docker run -p 80:8080 -m 256m --cpus=".5" -d roman20003821/node-js-on-docker:1