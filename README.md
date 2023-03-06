# Практична робота #3
## Збудувати docker image
    docker build . -t romansmakula/node-js-on-docker

## Запустити контейнер з обмеженними memory та cpu
    docker run -p 80:8080 -m 256m --cpus=".5" -d romansmakula/node-js-on-docker