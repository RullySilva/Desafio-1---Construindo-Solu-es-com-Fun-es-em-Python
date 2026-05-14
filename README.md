# Desafio-1---Construindo-Solu-es-com-Fun-es-em-Python
1 / 3 - Clientes Exclusivos: Filtrando Dados Sem Duplicidade

linha1 = input().strip()

linha2 = input().strip()

clientes_projeto1 = set(linha1.split())

clientes_projeto2 = set(linha2.split())

exclusivos = clientes_projeto1.symmetric_difference(clientes_projeto2)

if exclusivos:

    print(' '.join(sorted(exclusivos)))
    
else:

    print("Nenhum")
