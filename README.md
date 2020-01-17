# Todo-golang-react
A simple golang RESTful API

### Commands (container)
```bash
# build app/ui docker images
$ make build

# start app/ui containers
$ make up

# rebuild app/ui images
$ make rebuild
```

For now, to run locally:
```bash
# install dependencies
$ yarn install

# start frontend dev server
$ yarn start

# build backend go app
$ docker-compose build app

# run app
$ docker-compose run app

# navigate to http://localhost:8080 in your browser
```

#### Accessible via:
* Frontend - http://localhost:8080
* API - http://localhost:5001/api/v1/todos/
