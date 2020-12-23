# FIAP NodeJS
<p align="left">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Relirk/fiap-nodejs">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Relirk/fiap-nodejs">
  
  <a href="https://github.com/Relirk/fiap-nodejs/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Relirk/fiap-nodejs">
  </a>

  <a href="https://github.com/Relirk/fiap-nodejs/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/Relirk/fiap-nodejs">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
</p>

Projeto para conclusão da disciplina de NodeJS, ministrada em dezembro de 2020

![FIAP](fiap_mba.png)

#Inserir
```json
mutation {
  inserir(
    id: 4
    nomeproduto: "Notebook"
    descricao: "Notebook Samsung"
    fornecedor: "Samsung"
    preco: 4500.00
    datacadastro: "22/12/2020"
  ){
    id
    nomeproduto
    descricao
    fornecedor
    preco
    datacadastro
  }
}
```

#Atualizar
```json
mutation {
  atualizar(
    id: 4
    nomeproduto: "Notebook"
    descricao: "Notebook Samsung"
    fornecedor: "Samsung"
    preco: 4500.00
    datacadastro: "22/12/2020"
  ){
    id
    nomeproduto
    descricao
    fornecedor
    preco
    datacadastro
  }
}
```

#Excluir
```json
mutation {
  excluir(
    id: 5
  ){
    id
  }
}
```

Resultado do professor avaliador + banca

![FIAP]()
