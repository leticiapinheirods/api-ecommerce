# ⚙️ API de E-commerce com Python sem frameworks 
Este é um projeto que contém uma API de e-commerce, desenvolvida com Python e sem o uso de frameworks, com o intuito de praticar e aprimorar minhas habilidades no back-end, permitindo uma compreensão mais profunda dos componontes que formam esse tipo de aplicação.

## 🚧 Status do projeto - em fase de desenvolvimento 🚧

Atualmente, a API está sendo configurada e os passos realizados foram:

✅**Configuração do ambiente com Docker:** Isso facilita a replicação do ambiente em diferentes máquinas.

✅**Modelagem do banco de dados:** Foram definidas as tabelas e relacionamentos para armazenar dados de usuários, produtos, carrinhos e pedidos.

### Diagrama de relacionamentos e entidades

<div align="center">
  <img src="DER\der_api_ecommerce.png" alt="DER da api" width="800">
</div>

### Próximo passo

◻️**Criação do servidor HTTP**: Implementação do servidor HTTP para gerenciar as requisições e rotas da API.

## 🚀 Como rodar o projeto

### Pré-requisitos
1. Fazer o [download](https://www.docker.com/) do Docker Desktop na sua máquina

2. Inicie o aplicativo do Docker Desktop

### Iniciando o ambiente Docker

1. Clone este repositório no seu terminal:
```
git clone https://github.com/leticiapinheirods/api-ecommerce.git
```
2. No diretório principal, crie um arquivo `.env` e defina as seguintes variaveis de ambiente para conexão com o banco de dados:

```
DATABASE_URL=
DB_USER=
DB_PASSWORD=
DB_NAME=
```

3. No diretório onde o arquivo `docker-compose.yml` está localizado, execute o comando abaixo para construir os containers Docker:
```
docker-compose build
```

4. Inicie todos os containers criados anteriormente:
```
docker-compose up
```

5. Quando o comando terminar, você verá a aplicação rodando em `http://localhost:5000/`

## 🤝 Contribuições

Este projeto está em desenvolvimento e está aberto para contribuições. Fique à vontade para abrir uma issue ou enviar um pull request!