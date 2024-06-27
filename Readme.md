# Docker app

## Сбилдить

```shell
docker build --tag hexlet-app:1.0.0 . 
```

## Запустить с пробросом портов

````shell
docker run -p 3001:3000 hexlet-app:1.0.0
````