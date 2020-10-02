[![Docker Image CI](https://github.com/shunak/docker-react-typescript-development-environment/workflows/Docker%20Image%20CI/badge.svg)](https://github.com/shunak/docker-react-typescript-development-environment/actions?query=workflow%3A%22Docker+Image+CI%22)<br>
react-typescript development environment on docker. <br>
by using docker, node version management is easily.

## How to use
```
git clone https://github.com/shunak/docker-react-typescript-development-environment.git
```
```
cd docker-react-typescript-development-environment
```
```
docker-compose build
```
```
docker-compose run --rm node sh -c 'npx create-react-app sample_app --template typescript'
```
### start application
```
docker-compose up
```
URL: http://localhost:3000/ or http://0.0.0.0:3000/

### shut down application
```
docker-compose down
```


