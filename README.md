# Docker liferay-6.2-ce-ga6 postgres Developer Environment

## Requisitos
```
Docker version 17.09.0-ce or > .
docker-compose version 1.18.0 or > .
```

## Docker Liferay Postgres Developer
#### Executando
```
docker-compose up -d

```

Acesso: [localhost:8282](http://localhost:8282)

## Usando o sdk na sua IDE

#### Altere o nome build.user.properties para o nome do usuário do host
```
build.nomedousuariodohost.properties
Ex: build.rafael.properties

```

## Atualize o caminho app.server.parent.dir em build.nomedousuariodohost.properties
#### Carrega as libs do liferay-portal para usar o plugin sdk

```
app.server.parent.dir = /seudiretorio/docker-liferay-postgres-dev/lib/liferay-portal-lite-lib

```

## Definir o diretorio do projeto sdk na IDE e criar seu plugin liferay

## Use o Ant na sua IDE ou local para criar plugins. O sdk está configurado para fazer deploy em tmp/deploy

## Login
```
E-mail: test@liferay.com
Senha: test

```
