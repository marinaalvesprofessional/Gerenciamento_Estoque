# 📦 Sistema de Gerenciamento de Estoque em Python

Sistema desenvolvido em Python para realizar o gerenciamento básico de produtos em estoque, permitindo cadastrar, atualizar, consultar e controlar a entrada e saída de mercadorias.

O programa funciona por meio de um menu interativo no terminal, facilitando o controle das quantidades, dos preços e das categorias dos produtos.

---

## 📌 Sobre o projeto

O Sistema de Gerenciamento de Estoque foi desenvolvido com o objetivo de aplicar conceitos fundamentais de programação utilizando a linguagem Python.

A aplicação permite organizar produtos, acompanhar a quantidade disponível e calcular o valor total dos itens cadastrados.

O código foi organizado em funções, separando as principais operações do sistema para facilitar a compreensão, a manutenção e a reutilização.

## ⚙️ Funcionalidades

O sistema possui sete opções principais:

| Opção | Funcionalidade | Descrição |
|:---:|---|---|
| 01 | Cadastrar produtos | Adiciona novos produtos ao estoque. |
| 02 | Atualizar produtos | Atualiza a quantidade, o preço e a categoria de produtos cadastrados. |
| 03 | Consultar estoque | Exibe os produtos, categorias, quantidades e preços. |
| 04 | Valor total | Calcula o valor total dos produtos armazenados. |
| 05 | Estoque baixo | Identifica produtos que estão abaixo de uma quantidade definida. |
| 06 | Registrar entrada | Adiciona unidades ao estoque de um produto existente. |
| 07 | Registrar saída | Remove unidades do estoque, verificando a quantidade disponível. |

## 💻 Tecnologias utilizadas

- **Python:** linguagem utilizada no desenvolvimento da aplicação.
- **Dicionários:** armazenamento dos produtos e suas informações.
- **Listas:** organização dos dados de cada produto, como quantidade, preço e categoria.

## 🧠 Conceitos de programação aplicados

Durante o desenvolvimento, foram utilizados:

- **Funções:** divisão das funcionalidades em blocos independentes.
- **Estruturas condicionais:** utilização de `if`, `elif` e `else` para controlar as operações.
- **Estruturas de repetição:** utilização de `while` e `for` para manter o menu ativo e percorrer os produtos.
- **Dicionários:** armazenamento dos produtos utilizando seus nomes como identificação.
- **Listas:** organização das informações de cada produto.
- **Tratamento de erros:** utilização de `try` e `except` para evitar interrupções quando o usuário digita valores não numéricos.
- **Manipulação de strings:** utilização de `strip()` e `title()` para padronizar os nomes e categorias.
- **Validação de dados:** verificações para impedir valores negativos e saídas maiores que a quantidade disponível.
- **Operadores aritméticos:** cálculos de quantidade e valor total do estoque.

## 📂 Estrutura do projeto

O projeto está organizado em um único arquivo Python, contendo todas as funções e o menu principal.

```text
gerenciamento-de-estoque/
│
├── estoque.py
│   └── Funções e menu principal do sistema.
│
└
