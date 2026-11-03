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
python estoque.py
```

> É necessário ter o Python instalado no computador.

## 💾 Armazenamento de dados

Atualmente, os produtos são armazenados em um dicionário durante a execução do programa.

Isso significa que as informações cadastradas permanecem disponíveis enquanto o sistema está aberto, mas são perdidas quando o programa é encerrado.

Uma possível melhoria futura seria implementar o armazenamento em arquivos JSON ou em um banco de dados MySQL.

## 📷 Demonstração

O sistema apresenta um menu interativo no terminal, permitindo que o usuário escolha as operações de gerenciamento.

Sugestões de capturas de tela:

- Menu principal do sistema.
- Cadastro de um novo produto.
- Consulta dos produtos cadastrados.
- Cálculo do valor total do estoque.
- Registro de entrada e saída de produtos.

## 🎯 Objetivo acadêmico

O projeto tem como finalidade desenvolver conhecimentos práticos em Python, trabalhando principalmente com funções, estruturas condicionais, estruturas de repetição, listas, dicionários e tratamento de erros.

Além disso, busca demonstrar como a programação pode ser utilizada para solucionar situações do cotidiano, como o controle e a organização de produtos em um estoque.

## 👩‍💻 Autora

**Marina Alves**

Estudante de Análise e Desenvolvimento de Sistemas — 2º semestre

UDF — Centro Universitário

---

*Projeto acadêmico desenvolvido para fins de aprendizagem e prática de programação em Python.*
