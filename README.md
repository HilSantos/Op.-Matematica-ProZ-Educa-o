# Op.-Matematica-ProZ-Educacao
Crie uma calculadora em Python

import os

def calculadora(n1,n2):

  opcao = 1
  while opcao:  
    op = float(input("Escolha a operacao - 1. soma, 2. subtracao, 3. divisao 4. multiplicacao 0. sair:"))
    n1 = float(input("Digite um numero:"))
    n2 = float(input("Digite um numero:"))

  opcao = int(input("opção: "))  
    

  if op==1:
      print("soma: ", n1+n2) 
    elif op==2:
      operacao = n1-n2

  elif op==3:
      operacao = n1*n2
      
  elif op==4:
      operacao = n1/n2
    
  opcao = int(input("Digite 0 para Sair"))

  print(operacao)

  if opcao == 0:
      sair = True

  calculadora()

  print("Digite um numero")
numero = int(input())
res = numero + 5
print("O numero digitado mais 5 igual a " + str(res))

print("Escreva abaixo o seu nome")
nome = input()
mensagem = "Bem vindo " + nome
print(mensagem)
