# GOPPORTUNITIES

![CI Status](https://github.com/soupaulodev/gopportunities/actions/workflows/orchestrate.yml/badge.svg) ![Build Status](https://github.com/soupaulodev/gopportunities/actions/workflows/build.yml/badge.svg) ![Test Status](https://github.com/soupaulodev/gopportunities/actions/workflows/test.yml/badge.svg) ![Merge Status](https://github.com/soupaulodev/gopportunities/actions/workflows/merge.yml/badge.svg)

![Gopher image](https://miro.medium.com/v2/resize:fit:735/1*_d8_TuE2kIsZnCSEamV4jA.jpeg)

## Descrição

GOpportunities é uma simples RestFull API escrita em [Go](https://golang.org/dl/) utilizando o web framework [Gin Gonic](https://github.com/gin-gonic/gin) para gerenciamento de vagas de emprego.

## Pré-requisitos

Para desenvolver o projeto, você precisa ter o [Go](https://golang.org/dl/) na versão 1.23.\* e o [Docker](https://www.docker.com/) instalado em sua máquina.

Para verificar se você já tem o Go instalado, execute o seguinte comando:

```sh
go version
```

Para verificar se você já tem o Docker instalado, execute o seguinte comando:

```sh
docker version
```

Caso você não tenha o Go ou o Docker instalado, acesse a [golang.org](https://golang.org/dl/) e [Docker](https://www.docker.com/) e siga as instruções de instalação.

## Executando em Desenvolvimento

### Para clonar o repositório, execute o seguinte comando

```sh
git clone https://github.com/soupaulodev/togo
```

### Subindo os containers docker

Na raiz do projeto, execute:

```sh
docker compose up -d
```

### Executando o projeto

```sh
go run main.go
```

## Licença

This project is licensed under the MIT License - see the [license](https://github.com/soupaulodev/gopportunities/blob/main/LICENSE) file for details.

## Contribuindo

First of all, thank you for considering contributing to this project. Any help is appreciated. If you want to contribute, follow these steps:

1. Fork the project
2. Create a new branch (`git checkout -b feature/feature-name`)
3. Make the changes
4. Commit the changes
5. Push to the branch (`git push origin feature/feature-name`)
6. Create a new Pull Request
