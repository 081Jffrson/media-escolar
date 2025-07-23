# media-escolar
Programa em Python que calcula média de duas notas e informa se o aluno foi aprovado, em recuperação ou reprovado.
nome = input('Digite seu nome: ')
idade = int(input('Digite sua idade: '))
print(f'Olá {nome}, Seja bem-vindo!')

n1 = float(input('Digite sua nota: '))
n2 = float(input('Digite sua segunda nota: '))

media = (n1 + n2)/2

print(f'Sua média foi: {media:.2f}')

if media >= 7:
    print(f'Parabéns {nome}, você está: APROVADO!!')
elif media >= 5:
    print(f'{nome}, você está em RECUPERAÇÃO.')
else:
    print(f'Infelizmente você não foi aprovado {nome}, boa sorte na próxima.')

