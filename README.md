# Calculadora
#Introdução da calculadora

print("\nBem vindo, essa é a calculadora.")     #Pegando informações com usuário
nome = input ("\nQual é o seu nome?  ")
print("\nO que vamos calcular hoje",nome,"?!")

#Definindo as operações

#Adição
def soma(num1, num2):       # Def inicia a definição da função
  return num1 + num2        # Return encerra a definição da função
  print(soma(num1, num2))

#Subtração
def subtração(num1, num2):
  return num1 - num2
  print(subtração(num1, num2))

#Divisão
def divisão(num1, num2):
  if num2 == 0:
    return "Não é possível dividir por zero!"
  return num1 / num2
  print(divisão(num1, num2))

#Multiplicação
def multiplicação(num1, num2):
  return num1 * num2
  print(multiplicação(num1, num2))

# Loop infinito para repetir as operações
while True:
    # Pegando os números e a operação do usuário
    num1 = float(input("\nDigite o primeiro número: "))
    operação = input("\nDigite a operação (+, -, *, /): ")
    num2 = float(input("\nDigite o segundo número: "))
    #Calculando e exibindo o resultado
    print("\nResultado: ")
    if operação == "+":
        print(soma(num1, num2))
    elif operação == "-":
        print(subtração(num1, num2))
    elif operação == "/":
        print(divisão(num1, num2))
    elif operação == "*":
        print(multiplicação(num1, num2))
    else:
        print("\nOperação inválida!")

# Perguntar se deseja continuar
    while True:  # Loop para garantir que o usuário escolha uma opção válida
        escolha = input("\nDeseja fazer outra operação? (1. Sim / 2. Não): ")
        if escolha == "1":
            print("\nOk, vamos lá!")
            break  # Volta para o loop principal e repete a operação
        elif escolha == "2":
            print("\nAté a próxima!")
            break  # Sai do loop interno
        else:
            print("\nOpção inválida! Digite 1 para continuar ou 2 para sair.")

    if escolha == "2":  # Verifica se o usuário quer sair
        break  # Sai do loop principal e finaliza o programa



#                   By: Alessandro S Souza
