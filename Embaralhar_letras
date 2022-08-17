import random
from time import sleep

frases_motivacao = ['Corre, vai dar bom.', 'Continue a nadar,continue a nadar..',
                    'Tenta novamente, vai dar bom guerreiro', 'Meu Deus.. Meu Senhor.. Me Ajuda, POR FAVOR', 'Catapimbas meo, você quase acertou']
tentativa = 5
cont = 0

palavras = 'ABACAXI', 'PROGRAMA', 'PARALELEPÍPEDO', 'GABRIEL', 'VIVAOLINUX', 'PYTHON', 'CACHORRO', 'MACARRÃO', 'FERRARI', 'VERMELHO', 'EDUARDA', 'PESQUISAR'
sorteado = random.choice(palavras)
while tentativa != 0:
    embaralha = random.sample(sorteado, len(sorteado))
    juntar_palavra_embaralhada = ''.join(embaralha)
    print(juntar_palavra_embaralhada)
    print("="*20)
    tent = input("Digite a palavra: ").upper()
    print("\033[36;47m\n SERÁ QUE VOCÊ ACERTOU?\033[m")
    sleep(2)

    if tent == sorteado:
        s = print(
            f"\033[30;42m\nRECEBAAAA! Você é o bichão mermo!\U0001F606 {tentativa}/5 chances\033[m")

        break

    if tentativa == 0:
        print(
            f'A palavra correta era {sorteado}, {tentativa}/5 chances')
        break

    else:
        print()
        print(f'\033[31m{frases_motivacao[cont]}\033[m')
        cont += 1

    tentativa -= 1
    print(f'{tentativa} tentativa(s) restante(s)')

    if tentativa == 0:

        print(
            f'A palavra correta era {sorteado}, {tentativa}/5 chances')
        break
