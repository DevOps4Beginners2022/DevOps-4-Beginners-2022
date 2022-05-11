# Todos

### Build and run all components

``` sh
docker-compose build
docker-compose run --rm backend bundle install
docker-compose run --rm backend rails db:create db:migrate
docker-compose up/down
```

### Rails api console

``` sh
docker-compose run --rm backend rails console
```

### Run api tests

``` sh
docker-compose run --rm backend rails test
```
