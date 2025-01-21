# Calculadora.sh

Para executar a calculadora.sh, digite no Power Shell o comando 

./calculadora.sh


# Calculadora.py

## O código da calculadora.py

 
nome = input("Digite seu nome: ") #Aqui criamos a variável nome, onde o usuário irá inserir seu nome.
print("Olá", nome, "seja bem vindo/a!") #Interação com o usuário
print(nome, "vamos utilizar a calculadora!") #Interação com o usuário

num1 = float(input("Digite o primeiro número: ")) #Aqui criamos uma variável para números decimais
num2 = float(input("Digite o segundo número:" ))  #Aqui criamos uma variável para números decimais

print(nome, "Abaixo está os resultados calculados!") #Interação com usuário
print("Soma: ", num1 + num2) #Resultado da soma dos números inseridos
print("Subtração: ", num1 - num2) #Resultado da subtração dos números inseridos
print("Multiplicação: ", num1 * num2) #Resultado da multiplicação dos números inseridos
print("Divisão: ", num1 / num2) #Resultado da divisão dos números inseridos
if num1 > num2: #Condicional para saber qual o maior número
  print("O maior número digitado é: ", num1)
elif num2 > num1:
  print("O maior número digitado é: ", num2)
else:
  print("Os números são iguais!")
