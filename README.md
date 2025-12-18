# Sistema Bancário Otimizado com Funções em Python

Este repositório contém uma aplicação de console em Python que simula as operações de um sistema bancário. O projeto foca em organização de código, utilizando funções para modularizar a lógica de depósitos, saques e gerenciamento de usuários.

## 🚀 Funcionalidades

- **Gerenciamento de Usuários:** Cadastro de clientes com CPF (único), nome, data de nascimento e endereço.
- **Gerenciamento de Contas:** Criação de contas corrente vinculadas a usuários cadastrados, com numeração sequencial e agência fixa.
- **Operações Financeiras:**
    - **Depósito:** Recebe valores positivos e atualiza o saldo (argumentos via posição).
    - **Saque:** Controle de limite por transação (R$ 500,00) e limite diário de saques (3), com verificação de saldo insuficiente (argumentos via nome).
    - **Extrato:** Exibição detalhada de todas as movimentações e saldo atual.

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Biblioteca `textwrap`:** Utilizada para formatação de strings e menus.

## 📋 Estrutura de Funções

O projeto segue regras rígidas de parâmetros para demonstrar o poder da sintaxe Python:
- `depositar`: Argumentos por posição (`/`).
- `sacar`: Argumentos por nome (`*`).
- `exibir_extrato`: Argumentos híbridos (posicionais e nomeados).

## 🔧 Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório ou copie o código fonte.
3. Execute o script principal:
   ```bash
   python desafio.py
