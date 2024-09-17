# Entradas
valor_casa = float(input("Valor da casa: R$ "))
salario = float(input("Salário: R$ "))
anos = int(input("Quantos anos para pagar: "))

# Cálculos
meses = anos * 12
prestacao = valor_casa / meses

# Verificação
if prestacao <= salario * 0.30:
    print("Empréstimo aprovado!")
else:
    print("Empréstimo negado!")
