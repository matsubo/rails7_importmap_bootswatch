# README

Skelton project of Rails7 + importmap + dartsass-rails.
UI design is bootswatch.

## Screenshot

![image](https://user-images.githubusercontent.com/98103/195979513-8f142391-9b79-4d12-a52e-78ee133978d9.png)


## Setup

```
docker-compose build
docker-compose run node yarn
```

## Run


```
docker-compose up
```

## Assets precompile


```
docker-compose run --rm app bundle exec rails assets:precompile
```

