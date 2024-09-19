import time
print("{} Menu de Opções {}".format("-=" * 5, "-=" * 5))
n1 = int(input("Primeiro valor: "))
n2 = int(input("Segundo valor: "))
resposta = 0
while resposta != 5:
    print("=-="*10)
    print("Informe oque você desejar!")
    print("[1] Somar\n[2] Multiplicar\n[3] Maior\n[4] Novos numeros\n[5] Sair do programa\n")
    print("=-=" * 10)
    resposta = int(input("Qual é sua opção: "))
    while resposta < 1 or resposta > 5:
        resposta = int(input("VALOR INVÁLIDO. Digite novamente sua opção: "))
    if resposta == 1:
        print("A soma de {} e {} é igual a {}".format(n1, n2, n1 + n2))
    if resposta == 2:
        print("A multiplicação de {} e {} é igual a {}".format(n1, n2, n1 * n2))
    if resposta == 3:
        if n1 > n2:
            maior = n1
        else:
            maior = n2
        print("Entre {} e {} o maior é {}".format(n1, n2, maior))
    if resposta == 4:
        print("Informe os números novamente!")
        n1 = int(input("Primeiro valor: "))
        n2 = int(input("Segundo valor: "))
print("Finalizando...")
time.sleep(2)
print("Programa finalizado!")
