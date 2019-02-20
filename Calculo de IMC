from time import sleep

nome = input('Digite o seu primeiro nome: ').strip().capitalize().split()
print('Olá {}, por favor preencha o formulário abaixo, para calcularmos o seu IMC!'.format(nome[0]))
massa = float(input('Digite o seu peso: '))
altura = float(input('Digite a sua altura: '))
print()
altura = altura ** 2  #poderia ter feito em uma linha  massa / (altura ** 2)
imc = massa / altura
print('{}, Obrigado por preencher o formulário, agora iremos calcular o seu IMC para você!'.format(nome[0]))
print()
tempo = sleep(0.6)

print('Calculando...')
sleep(1)

if imc <= 16.99:
    print('{}. Seu IMC é{:.1f} Situação: \033[4;31;0mMUITO ABAIXO DO PESO, PROCURE UM MÉDICO\033[m!!'.format(nome[0],imc))

elif imc >= 17 and imc <= 18.49:
    print('{}, Seu IMC é {:.1f} Situação: \033[4;31;0mABAIXO DO PESO\033[M '.format(nome[0], imc))

elif imc >= 18.5 and imc <= 24.99:
    print('{}, Seu IMC é {:.1f} Situação: \033[4;34;0mPESO IDEAL\033[m'.format(nome[0], imc))

elif imc >= 25 and imc <= 29.99:
    print('{}. Seu IMC é {:.1f} Situação: \033[4;32;0mSOBREPESO\033[m'.format(nome[0], imc))

elif imc >= 30 and imc <= 34.99:
    print('{}. Seu IMC é {:.1f} Situação: \033[4;31;0mOBESIDADE 1, PROCURE UM MÉDICO!\033[m'.format(nome[0], imc))

elif imc >= 35 and imc <= 39.99:
    print(f'{nome[0]}.Seu IMC é {imc:.1f} Situação:  \033[4;31;0mOBESIDADE 2 (SEVERA). PROCURE UM MÉDICO\033[m')

elif imc >= 40:
    print(f'{nome[0]}. Seu IMC é {imc:.1f} Situação: \033[4;31;0mOBESIDADE 3 (MÓRBIDA. PROCURE UM ESPECIALISTA)\033[m')
