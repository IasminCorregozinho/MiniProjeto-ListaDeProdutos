# 🛒 Lista de produtos

Um mini projeto para gerenciar uma lista de produtos via console.

## ✍️ Autores

  - Fabiana Chaves
  - Iasmin Corregozinho
  - Isabella Fernandes

## 📄 Sobre o Projeto

Este projeto é um console interativo que permite aos usuários gerenciar uma lista de produtos. As funcionalidades incluem:

  - **Adicionar Produtos:** Insira o nome, preço e quantidade de um item.
  - **Listar Produtos:** Exibe todos os produtos que foram acrescentados.
  - **Calcular Valor Total:** Calcula o valor total em estoque com base no preço e na quantidade de cada produto.

## 🛠️ Como Executar

Para rodar a aplicação localmente, siga os seguintes passos:

1.  Instale as dependências do projeto:
    ```sh
    npm install
    ```
2.  Execute o script principal:
    ```sh
    node index.js
    ```

## 🖥️ Exemplo de Uso

Abaixo, você pode ver um exemplo de como o programa funciona, desde a adição de produtos até a exibição da lista e do valor total.

```sh
--- MENU DE OPÇÕES ---
1. Adicionar produtos:
2. Listar produtos
3. Sair
----------------------
Escolha uma opção: 1
Qual item deseja adicionar? Arroz
Digite o preço do produto: 21.90
Digite a quantidade do produto: 2
Arroz adicionado à lista.

--- MENU DE OPÇÕES ---
1. Adicionar produtos:
2. Listar produtos
3. Sair
----------------------
Escolha uma opção: 1
Qual item deseja adicionar? Feijão
Digite o preço do produto: 11.90
Digite a quantidade do produto: 4
Feijão adicionado à lista.

--- MENU DE OPÇÕES ---
1. Adicionar produtos:
2. Listar produtos
3. Sair
----------------------
Escolha uma opção: 2
 ---Aqui está sua e-Wish List:-----
- 1. Arroz - R$ 21.90 - Quantidade: 2
- 2. Feijão - R$ 11.90 - Quantidade: 4
Valor total da lista: R$ 91.40

--- MENU DE OPÇÕES ---
1. Adicionar produtos:
2. Listar produtos
3. Sair
----------------------
Escolha uma opção: 3
Finalizado. Até mais!
```
