# 🧮 Calculadora em Python

Este projeto é uma calculadora simples criada em Python, que realiza as quatro operações básicas: **adição, subtração, multiplicação e divisão**, com uma interação amigável via terminal.

## 👤 Desenvolvedor
By: Alessandro S Souza

## 🚀 Funcionalidades

- Recebe o nome do usuário
- Realiza as operações: soma, subtração, multiplicação e divisão
- Valida divisão por zero
- Permite ao usuário repetir quantas vezes quiser
- Mensagens amigáveis no terminal

## ▶️ Como Executar

### 1. Executando com Python

```bash
python3 calculadora.py
```

### 2. Usando o script `.sh` (Linux/macOS)

Crie um arquivo chamado `executar.sh` com o conteúdo abaixo:

```bash
#!/bin/bash
python3 calculadora.py
```

Depois, dê permissão de execução:

```bash
chmod +x executar.sh
./executar.sh
```

## 🗂 Estrutura do Projeto

```
calculadora/
├── calculadora.py    # Código-fonte da calculadora
├── executar.sh       # Script para execução rápida (Linux/macOS)
└── README.md         # Documentação do projeto
```

## 🧠 Lógica do Código

- Define funções para as quatro operações matemáticas
- Recebe os dois números do usuário e a operação desejada
- Executa a operação selecionada
- Repete enquanto o usuário quiser continuar

## ⚠️ Observações

- A entrada é validada para evitar divisão por zero
- O script é interativo e roda no terminal
