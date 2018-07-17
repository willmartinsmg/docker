# Comandos Docker

Lista de comandos utéis

Para todas as instâncias
```
docker stop $(docker ps -a -q)
```

Remove todas as instâncias
```
docker rm $(docker ps -a -q)
```

Para todas as imagens
```
docker image rm $(docker image ls -a -q)
```

Comandos retirados do site de [Emerson Barros](https://emersonbarros.com.br/docker-parar-remover-todos-os-containers-docker/).
