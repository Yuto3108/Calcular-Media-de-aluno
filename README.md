# Definindo as variáveis
qtd_alunos = 2

# Solicitando as notas do aluno 1
print("Qual é a nota da primeira prova do aluno 1?")
prova_aluno1 = float(input())
if prova_aluno1 >= 0.0:
    print("Qual é a nota do trabalho do aluno 1?")
    trabalho_aluno1 = float(input())
    if trabalho_aluno1 >= 0.0:
        print("Qual é a nota da segunda prova do aluno 1?")
        prova2_aluno1 = float(input())
        if prova2_aluno1 >= 0.0:
            notas_aluno1 = prova_aluno1 + trabalho_aluno1 + prova2_aluno1
            media_aluno1 = notas_aluno1 / 3.0
            print("A média do aluno 1 é:", media_aluno1)

# Solicitando as notas do aluno 2
print("Qual é a nota da primeira prova do aluno 2?")
prova_aluno2 = float(input())
if prova_aluno2 >= 0.0:
    print("Qual é a nota do trabalho do aluno 2?")
    trabalho_aluno2 = float(input())
    if trabalho_aluno2 >= 0.0:
        print("Qual é a nota da segunda prova do aluno 2?")
        prova2_aluno2 = float(input())
        if prova2_aluno2 >= 0.0:
            notas_aluno2 = prova_aluno2 + trabalho_aluno2 + prova2_aluno2
            media_aluno2 = notas_aluno2 / 3.0
            print("A média do aluno 2 é:", media_aluno2)

# Calculando a média geral
media_geral = (media_aluno1 + media_aluno2) / qtd_alunos
print("A média dos alunos é:", media_geral)
