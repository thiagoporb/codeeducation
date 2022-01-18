# Desafio Go - modulo iniciando com docker. 

### Este desafio tem como objetivo publicar uma imagem no docker hub. Quando executarmos:

```
./docker run thiagoporb/codeeducation
```
Obs. A imagem do projeto Go precisa ter menos de 2MB =)

# Instalação

## Pré-requisitos

Para executar o desafio, você precisará das seguintes tecnologias.

1. Docker [site do Docker] (https://www.docker.com/get-started)

2. Go ou superior do [site do Golang] (https://go.dev/doc/install)

### Essa imagem apenas realiza um print da mensagem "Code.education Rocks!" como resultado.

## Rodando a aplicação

Build: 
```
./go run main.go
```

## Buildando a aplicação

Build: 
```
./go build -ldflags="-s -w"
```