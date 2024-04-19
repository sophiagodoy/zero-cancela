# Linha para imprimir uma linha de caracteres '-' 100 vezes
print(100*"-")

# Mensagem de boas-vindas ao jogo Zero Cancela
print("\t\tBEM VINDO AO ZERO CANCELA!")
print(100*"-")

# Explicação de como o jogo funciona
print("Como funciona o jogo:")
print("\t-> Você deve digitar quantos números quiser, quando digitar um negativo, a inserção de números é finalizada.")
print("\t-> Quando for necessário desconsiderar um número, digite 0. Você só pode usar essa função 3 vezes.\n")

# Inicialização de variáveis
soma = 0
numeros_considerados = 0
numeros_desconsiderados = 0
zeros_consecutivos = 0
a = 0
b = 0
c = 0
numero = 0

# Loop para receber os números do usuário
while numero >= 0:
    numero = int(input("Digite um número (digite um número negativo para sair): "))
    
    # Verifica se o número digitado é zero
    if numero == 0:
        zeros_consecutivos += 1
        if zeros_consecutivos >= 4:  # Verifica se foram digitados mais de 3 zeros consecutivos
            print("Você só pode digitar até 3 zeros seguidos.")
        else:
            if c != 0:
                soma -= c  # Desconsidera o último número digitado
                numeros_desconsiderados += 1
                numeros_considerados -= 1                
    else:
        zeros_consecutivos = 0  # Reseta o contador de zeros consecutivos
        if numero > 0:
            soma += numero
            numeros_considerados += 1
            a = b
            b = c
            c = numero

# Imprime uma linha de caracteres '-' 100 vezes
print(100*"-")

# Mensagem de fim de jogo
print(f"\t\t\tFIM DE JOGO")
print(100*"-")

# Imprime a soma e o número de números considerados e desconsiderados
print(f"SOMA: {soma}")
print(f"NÚMEROS CONSIDERADOS: {numeros_considerados}")
print(f"NÚMEROS DESCONSIDERADOS: {numeros_desconsiderados}")
