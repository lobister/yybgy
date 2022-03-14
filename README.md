# yybgy
print('Ola, bem vido ao nosso restaurante, qual seu nome?')
nome=input()
print('Aqui servimos pizza e macarrao, qual o semhor vai querer?') 
escolha=input()

peperone=3
portuguesa=4
BRANCO=1
BOLONHESA=2



if escolha == 'pizza':
    print('para pizzas temos sabores de, peperone(3), portuguesa(4), ) digite o numero do sabor que o senho vai querer!!')  
else:
    print('para macarrao temos molhos, BRANCO (1), BOLONHESA(2) digite o numero do sabor que o senho vai querer!!')
    
sabor=int(input())

if sabor == 1:
    print('aguarde que seu macarrao ao molho branco esta sendo feito, assim que estiver seu nome sera chamado')
elif sabor == 2:
    print('aguarde que seu macarrao á bolonhesa esta sendo feito, assim que estiver seu nome sera chamado')
elif sabor == 3:
    print('aguarde que sua pizza de peperone esta sendo feita. assim que estiver, seu nome sera chamado')
elif sabor == 4:
    print('aguarde que sua pizza portuguesa esta sendo feita. assim que estiver, seu nome sera chamado')
