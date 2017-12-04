# Develop WorkSpace
Develop Golang & Node.js app quickly.

## Required
[docker & docker-compose](https://store.docker.com/search?type=edition&offering=community)

## Set Executable Path
See [docker-compose.yml](docker-compose.yml).

## Package Management
#### Golang
govendor

#### Node.js
npm

## Git Clone, Write Code and Run it !!
#### Golang
```
docker-compose up -d golang_test
```
![golang demo image](img/golang_demo.PNG)

#### Node.js
```
docker-compose up -d node_test
```
![nodejs demo image](img/nodejs_demo.PNG)

## Show Logs
#### Golang
```
docker-compose logs -f golang_test
```
![golang logs image](img/golang_logs.PNG)

#### Node.js
```
docker-compose logs -f node_test
```
![nodejs logs image](img/nodejs_logs.PNG)

## Kill All Service
```
docker-compose kill && docker-compose rm -f
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2017-present, Alex Lee