# Curso FullCycle - Desafio Docker com Golang
Projeto para criação de imagem docker com linguagem `go` e multi-stage builds.

## Objetivo
Imprimir mensagem no terminal com a linguagem `go` e gerar uma imagem com menos de `2MB`.

### Pré-Requisito
Ter instalado no seu ambiente:
- docker versão: 25.0.0

## Build de imagem com Docker local

Acesse o diretório em que o repositório foi clonado através do terminal e
execute os comandos:
 - `docker build -t "seu_usário_dockerhub"/"nome":latest . -f Dockerfile.prod` para gerar a imagem local;
 - `docker run --rm "nome_sua_imagem"` para imprimir a mensagem no terminal com a linguagem `go`

## Rodando imagem direto do repositório Docker Hub

Pelo terminal executar:

```
docker run --rm dantasdanddr/fullcycle 
```