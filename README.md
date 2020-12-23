#Inserir
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

#Atualizar
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

#Excluir
mutation {
  excluir(
    id: 5
  ){
    id
  }
}