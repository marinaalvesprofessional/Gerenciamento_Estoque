# 📦 Sistema de Gerenciamento de Estoque em Python

Sistema desenvolvido em Python para realizar o gerenciamento básico de produtos em estoque, permitindo cadastrar, atualizar, consultar e controlar a entrada e saída de mercadorias.

O programa funciona por meio de um menu interativo no terminal, facilitando o controle das quantidades, dos preços e das categorias dos produtos.

---

## 📌 Sobre o projeto

O Sistema de Gerenciamento de Estoque foi desenvolvido com o objetivo de aplicar conceitos fundamentais de programação utilizando a linguagem Python.

A aplicação permite organizar produtos, acompanhar a quantidade disponível e calcular o valor total dos itens cadastrados.

O código foi dividido em funções, separando as principais operações do sistema para facilitar a organização, a manutenção e a reutilização.

## ⚙️ Funcionalidades

O sistema possui sete opções principais:

| Opção | Funcionalidade | Descrição |
|:---:|---|---|
| 01 | Cadastrar produtos | Adiciona novos produtos ao estoque. |
| 02 | Atualizar produtos | Atualiza a quantidade e o preço de produtos já cadastrados. |
| 03 | Consultar estoque | Exibe os produtos, categorias, quantidades e preços. |
| 04 | Valor total | Calcula o valor total dos produtos armazenados. |
| 05 | Estoque baixo | Identifica produtos que estão abaixo de uma quantidade definida. |
| 06 | Registrar entrada | Adiciona unidades ao estoque de um produto existente. |
| 07 | Registrar saída | Remove unidades do estoque, verificando a quantidade disponível. |

## 💻 Tecnologias utilizadas

- **Python:** linguagem utilizada no desenvolvimento da aplicação.
- **Google Colab:** ambiente utilizado para desenvolver e executar o projeto.
- **Dicionários:** armazenamento das informações dos produtos.
- **Listas:** organização dos dados de cada produto.

## 🧠 Conceitos de programação aplicados

Durante o desenvolvimento, foram utilizados:

- **Funções:** divisão das funcionalidades em blocos independentes.
- **Estruturas condicionais:** utilização de `if`, `elif` e `else` para controlar as opções.
- **Estruturas de repetição:** utilização de `while` e `for` para manter o menu ativo e percorrer os produtos.
- **Dicionários:** armazenamento dos produtos e de suas informações.
- **Listas:** organização de quantidade, preço e categoria.
- **Tratamento de erros:** utilização de `try` e `except` para evitar erros na entrada de valores numéricos.
- **Manipulação de strings:** utilização de `strip()` e `title()` para padronizar os nomes dos produtos.
- **Validação de dados:** verificações para impedir quantidades negativas, preços inválidos e saídas maiores que o estoque disponível.
- **Modularização:** separação das funções em um arquivo independente (`estoque.py`).

## 📂 Estrutura do projeto

O projeto está organizado em dois arquivos principais:

```text
gerenciamento-de-estoque/
│
├── estoque.py
│   └── Funções responsáveis pelas operações do estoque.
│
├── main.py
│   └── Menu principal e interação com o usuário.
│
└── README.md
    └── Documentação do projeto.
```

## ▶️ Como executar o projeto

**1. Clone o repositório:**

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

**2. Acesse a pasta do projeto:**

```bash
cd gerenciamento-de-estoque
```

**3. Execute o programa:**

```bash
python main.py
```

> É necessário ter o Python instalado no computador. Os arquivos `main.py` e `estoque.py` devem permanecer na mesma pasta para que a importação das funções funcione corretamente.

## 📷 Demonstração

O sistema apresenta um menu interativo no terminal, permitindo que o usuário escolha as operações de gerenciamento.

*Adicione aqui capturas de tela mostrando o cadastro de produtos, a consulta do estoque e o registro de entrada ou saída.*

## 🎯 Objetivo acadêmico

O projeto tem como finalidade desenvolver conhecimentos práticos em Python, trabalhando principalmente com funções, estruturas de repetição, condicionais, listas, dicionários e tratamento de erros.

Além disso, busca demonstrar como a programação pode ser utilizada para solucionar situações do cotidiano, como o controle e a organização de produtos em um estoque.

## 👩‍💻 Autora

**Marina Alves**

Estudante de Análise e Desenvolvimento de Sistemas — 2º semestre

UDF — Centro Universitário

---

*Projeto acadêmico desenvolvido para fins de aprendizagem e prática de programação em Python.*
