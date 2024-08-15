# python_exercises
 college exercises
```python
#1ª Questão
numero = float(input('Digite um número: '))
print(f'o número informado foi {numero}.')
```





```python
#2ª Questão
numero1 = float(input('Digite o primeiro número:'))
numero2 = float(input('Digite o Segundo número:'))
soma = (numero1 + numero2)
print(f'A soma entre os dois números é {soma}.')
```





```python
#3ª Questão
nota1 = float(input('Digite a primeira nota: '))
nota2 = float(input('Digite a segunda nota: '))
nota3 = float(input('Digite a terceira nota: '))
nota4 = float(input('Digite a quarta nota: '))
media = (nota1 + nota2 + nota3 + nota4)/4
print(f'Sua média será {media:.1f}')
```





```python
#4ª Questão
metro = float(input('tamanho em metros: '))
cm = metro*100
print(f'convetendo {metro}m para cm, fica {cm}cm')
```





```python
#5ª Questão
raio = float(input('Digite um raio de um círculo: '))
area = 3.14*raio**2
print(f'A área do círculo é igual a {area:.2f} ')
```





```python
#6ª Questão
lado = float(input('Informe o lado do quadrado: '))
area = lado**2
print(f'O dobro da área do quadrago é igual a {area*2}')
```


```python
#7ª Questão
ganha_por_hr = float(input('quanto você ganha por hora? R$'))
hr_por_mes = int(input('Quantas horas você trabalhar por mês? '))
salario = ganha_por_hr * hr_por_mes
print(f'Seu salário total é de R${salario:.2f}')
```





```python
#8ª Questão
farenheit = float(input('Digite a temperatura em graus Farenheit: '))
celsius = (5*(farenheit-32)/9)
print(f'Transformando Farenheit em Celsius fica {celsius:.1f}°C')
```





```python
#9ª Questão
celsius = float(input('Digite a temperatura em graus Celsius: '))
farenheit = 1.8*celsius+32
print(f'Transformando Celsius em Farenheit fica {farenheit:.1f}°C')
```





```python
#10ª Questão
dolar = float(input('quanto você tem em $? '))
valor_dolar = float(input('valor do dolar:'))
real = float(dolar*valor_dolar)
print(f'você tem R${real:.2f}')
```





```python
#11ª Questão
valor = float(input('Valor depositado: R$'))
valor_rendimento = valor*1.007
print(f'O valor com o juros após um mês fica R${valor_rendimento:.1f}')
```





```python
#12ª Questão
valor = float(input('Valor da compra: R$'))
pratacoes = valor/5
print(f'O valor das prestaçoes será igual á {pratacoes}')
```





```python
#13ª Questão
preco_custo = float(input('Digite o preço de custo do produto:'))
acrecimo = float(input('Digite o acrécimo de preço de custo em porcentagem: '))
valor_venda = preco_custo * (1 + acrecimo/100)
print(f'o valor de venda será R${valor_venda:.2f}')
```





```python
#14ª Questão
distancia = float(input('Distância total pecorrida pelo automóvel em Km: '))
combustivel_gasto = float(input('Total de combustivel gasto: '))
consumo = distancia/combustivel_gasto
print(f'O consumo médio do automóvel é de {consumo:.1f}Km/L')
```





```python
#15ª Questão
a = int(input('Digite um valor positivo e inteiro para A: '))
b = int(input('Digite um valor positivo e inteiro para B: '))
c = int(input('Digite um valor positivo e inteiro para C: '))
r = (a + b)**2
s = (b + c)**2
d = (r + s)/2
print(f'O valor da expressão fica igual a {d}')
```





```python
#16ª Questão
nome = input('Nome do vendedor: ')
salario_fixo = float(input('Informe o seu salário fixo: '))
vendas = float(input('Informe o total de vendas efetuadas em dinheiro no mês: '))
comissao = vendas*0.15
salario_final = salario_fixo + comissao
print(f'Nome: {nome}\nSalário fixo: R${salario_fixo:.2f}\nSalário no final do mês: R${salario_final:.2f}')
```





```python
#17ª Questão
numero_int1 = int(input('Digite o primeiro número inteiro: '))
numero_int2 = int(input('Digite o segundo número inteiro: '))
numero_real = float(input('Digite um número real: '))
calculo1 = (numero_int1*2)*(numero_int2/2)
calculo2 = (numero_int1*3)+numero_real
calculo3 = numero_real**3
print(f'Resultado do primeiro calculo: {calculo1}\nResultado do segundo calculo: {calculo2}\nResultado do terceiro calculo: {calculo3}')
```





```python
#18ª Questão
altura = float(input('Informe sua altura: '))
peso_ideal = (72.7*altura)-58
print(f'O peso ideal para sua altura é {peso_ideal:.1f}Kg')
```





```python
#19ª Questão
tamanho_aquivo = float(input('Informe o tamanho do arquivo em MB: '))
velocidade_link = float(input('Infome a valocidade do link de internet em Mbps: '))
tempo_download = tamanho_aquivo/velocidade_link
print(f'O tempo aproximado de download do arquivo usando esse link será de {tempo_download:.1f} minutos.')
```





```python
#20ª Questão
a = int(input('Digite o valor de a: '))
b = int(input('Digite o valor de b: '))
a1 = a
a = b
b = a1
print(f'a = {a}\nb = {b}')

```





```python
#21ª Questão
ganha_por_hr = float(input('quanto você ganha por hora? R$'))
hr_por_mes = int(input('Quantas horas você trabalhar por mês? '))
salario = ganha_por_hr * hr_por_mes
ir = salario*0.11
inss = salario*0.08
sindicato = salario*0.05
salario_liq = salario - (ir + inss + sindicato)
print(f'O salário Bruto é igual a R${salario:.2f}')
print(f'Quanto pagou ao INSS: {inss}')
print(f'Quanto pagou ao sindicato: R${sindicato}')
print(f'O salário líquido é igual a R${salario_liq:.2f}')

```





```python
#22ª Questão
numero1 = float(input('Digite o primeiro número: '))
numero2 = float(input('Digite o segundo número: '))
if numero1 > numero2:
  print(f'O número maior é o {numero1}')
else:
  print(f'O número maior é o {numero2}')
```





```python
#23ª Questão
numero = float(input('Digite um número: '))
if numero == 0:
  print('O numero informado é neutro ')
else:
  if numero > 0:
    print('O numero informado é positivo ')
  if numero < 0:
    print('O numero informado é negativo ')
```





```python
#24ª Questão
sexo = input('Informe o seu sexo [M/F]: ')
if sexo in 'Mm':
  print('O sexo informado foi masculino.')
else:
  if sexo in 'Ff':
    print('O sexo informado foi feminino.')
  else:
    print('Sexo inválido.')
```





```python
#25ª Questão
nota1 = float(input('Informe sua primeira nota: '))
nota2 = float(input('Informe sua segunda nota: '))
media = (nota1 + nota2)/2
if media >=7 and media <10:
  print('Aprovado')
else:
  if media <7:
    print('Reprovado')
  if media == 10:
    print('Aprovado com Distinção')
  if media > 10:
    print('erro')
```





```python
#26ª Questão
numero1 = float(input('Digite o primeiro número: '))
numero2 = float(input('Digite o segundo número: '))
numero3 = float(input('Digite o terceiro número: '))
if numero1 > numero2 and numero1 > numero3:
  print(f'O número maior é o {numero1}')
else:
  if numero2 > numero1 and numero2 > numero3:
    print(f'O número maior é o {numero2}')
  else:
    print(f'O número maior é o {numero3}')
```

0



```python
#27ª Questão
valor1 = float(input('Informe o valor so primeiro produto: R$'))
valor2 = float(input('Informe o valor so segundo produto: R$'))
valor3 = float(input('Informe o valor so terceiro produto: R$'))
if valor1 < valor2 and valor1 < valor3:
  print(f'Você deve comprar o primeiro produto')
else:
  if valor2 < valor1 and valor2 < valor3:
    print(f'Você deve comprar o segundo produto')
  else:
    print(f'Você deve comprar o terceiro produto')
```





```python
#28ª Questão
turno = input('Informe o turno que você estuda [M/V/N]: ')
if turno in 'Mm':
  print('Bom dia!')
else:
  if turno in 'Vv':
    print('Boa tarde!')
  else:
    if turno in 'Nn':
      print('Boa noite!')
    else:
      print('Valor inválido.')
```





```python
#29ª Questão
salario = float(input('Salário do cobrador: '))
print(f'Salário antes do rajuste: {salario}')
porcentagem1 = 20/100
porcentagem2 = 15/100
porcentagem3 = 10/100
porcentagem4 = 4/100

if salario <= 280:
  print(f'Percentual de aumento: 20%')
  print(f'Valor do aumento: R${salario*porcentagem1:.2f}')
  print(f'Novo salário: R${salario*(1+porcentagem1):.2f}')
else:
  if salario > 280 and salario < 700:
    print(f'Percentual de aumento: 15%')
    print(f'Valor do aumento: R${salario*porcentagem2:.2f}')
    print(f'Novo salário: R${salario*(1+porcentagem2):.2f}')
  else:
    if salario > 700 and salario < 1500:
      print(f'Percentual de aumento: 10%')
      print(f'Valor do aumento: R${salario*porcentagem3:.2f}')
      print(f'Novo salário: R${salario*(1+porcentagem3):.2f}')
    else:
      print(f'Percentual de aumento: 5%')
      print(f'Valor do aumento: R${salario*porcentagem4:.2f}')
      print(f'Novo salário: R${salario*(1+porcentagem4):.2f}')
```





```python
#30ª Questão
ir = 0
ganha_por_hr = float(input('quanto você ganha por hora? R$'))
hr_por_mes = int(input('Quantas horas você trabalhar por mês? '))
salario = ganha_por_hr * hr_por_mes
sindicato = salario*0.03
fgts = salario*0.11
if salario <= 900:
  ir_porcentagem = 'insento'
else:
  if salario >900 and salario <= 1500:
    ir_porcentagem = int(5)
  else:
    if salario > 1500 <= 2500:
      ir_porcentagem = int(10)
    else:
      ir_porcentagem = int(20)
ir = salario*(ir_porcentagem/100)
total_descontos = ir + fgts + sindicato
salario_liq = salario - total_descontos
print('-'*60)
print(f'  i.     Salário Bruto:                :R${salario:.2f}')
print(f' ii.     Desconto do IR:               :R${ir:.2f}')
print(f'iii.     Desconto do Sindicato:        :R${sindicato:.2f}')
print(f' iv.     Desconto do FGTS:             :R${fgts:.2f}')
print(f'  v.     Total de desconto:            :R${total_descontos:.2f}')
print(f' vi.     Salário Líquido:              :R${salario_liq:.2f}')
```





```python
#31 Questão
numero = int(input('Digite um número de 1 a 7: '))
if numero == 1:
  print('Domingo')
else:
  if numero == 2:
    print('Segunda')
  else:
    if numero == 3:
      print('Terça')
    else:
      if numero == 4:
        print('Quarta')
      else:
        if numero == 5:
          print('Quinta')
        else:
          if numero == 6:
            print('Sexta')
          else:
            if numero == 7:
              print('Sábado')
            else:
              print('Valor inválido')
```





```python
#32 Questão
nota1 = float(input('Informe sua primeira nota: '))
nota2 = float(input('Informe sua segunda nota: '))
media = (nota1 + nota2)/2
if media >= 9 and media <= 10:
  conceito = 'A'
else:
  if media >= 7.5 and media  <9:
    conceito = 'B'
  else:
    if media >= 6 and media < 7.5:
       conceito = 'C'
    else:
      if media > 4 and media < 6:
        conceito = 'D'
      else:
        if media >= 0 and media < 4:
          conceito = 'E'
if conceito == 'A' or conceito == 'B' or conceito == 'C':
  mensagem = 'APROVADO'
else:
  mensagem = 'REPROVADO'
print(f'Primeira nota: {nota1}\nSegunda nota: {nota2}\nMédia: {media}')
print(f'Conceito: {conceito}\n{mensagem}')
```





```python
#33ª Questão
n1 = float(input('Primeiro segmento: '))
n3 = float(input('Segundo segmento: '))
n2 = float(input('Terceiro segmento: '))
if n1+n2 > n3 and n2+n3 > n1 and n1+n3 > n2:
    print('Os segmentos acima podem formar um triângulo', end=' ')
else:
    print('Os segmentos acima não podem formar um triângulo!')
if n1 != n2 != n3 != n1:
    print('escaleno!')
else:
  if n1 == n2 != n3 or n1 == n3 != n2 or n2 == n3 != n1:
    print('isóceles!')
  if n1 == n2 == n3:
    print('equilátero!')
```





```python
#34ª Questão
a = float(input('Informe o valor de a: '))
if a == 0:
  print('A equação não é do segundo grau.')
else:
  b = float(input('Informe o valor de b: '))
  c = float(input('Informe o valor de c: '))
  delta = (b**2) - (4*a*c)
  if delta < 0:
    print('A equação não possui raizes reais.')
  elif delta == 0 :
    print('A equação possui apenas uma raiz real:')
    x1 = (-(b) + delta**(1/2))/2*a
    x2 = (-(b) - delta**(1/2))/2*a
    print(f'x = {x}')
  elif delta > 0:
    print('A equação possui duas raizes reais:')
    x1 = (-b + delta**(1/2))/2*a
    x2 = (-b - delta**(1/2))/2*a
    print(f'x1 = {x1}\nx2 = {x2}')
```





```python
#35ª Questão
a = float(input('Informe o valor de a: '))
if a == 0:
  print('A equação não é do segundo grau.')
else:
  b = float(input('Informe o valor de b: '))
  c = float(input('Informe o valor de c: '))
  delta = (b**2) - (4*a*c)
  if delta < 0:
    print('A equação não possui raizes reais.')
  elif delta == 0 :
    print('A equação possui apenas uma raiz real:')
    x1 = (-(b) + delta**(1/2))/2*a
    x2 = (-(b) - delta**(1/2))/2*a
    print(f'x = {x}')
  elif delta > 0:
    print('A equação possui duas raizes reais:')
    x1 = (-b + delta**(1/2))/2*a
    x2 = (-b - delta**(1/2))/2*a
    print(f'x1 = {x1}\nx2 = {x2}')
```


```python
#36ª Questão
n = int(input('Digite o ano que quer analisar! Coloque 0 para analisar o ano atual:'))
if n == 0:
    print('O ano de 2024 é bissexto')
elif n % 4 == 0 and n % 100 != 0 or n % 400 == 0:
    print(f'O ano de {n} é bissexto')
else:
    print(f'O ano de {n} não é bissexto')
```





```python
#37ª Questão
nota1 = float(input('Informe sua primeira nota: '))
nota2 = float(input('Informe sua segunda nota: '))
nota3 = float(input('Informe sua terceira nota: '))
media = (nota1 + nota2 + nota3)/3
if media >=7 and media <10:
  print('Aprovado')
else:
  if media <7:
    print('Reprovado')
  if media == 10:
    print('Aprovado com Distinção')
  if media > 10:
    print('erro')
```





```python

#38ª Questão
dinheiro = int(input('Digite o valor de saque[min:R$10,max:R$600]: '))
cem = dinheiro//100
print(f'para sacar um quantidade R${dinheiro}, o progama fornece', end=' ')
if cem == 1:
  print(f'uma nota de 100,')
else:
  if cem == 2:
    print(f'duas notas de 100,')
  else:
    if cem == 3:
      print(f'três notas de 100,')
    else:
      if cem == 4:
        print(f'quatro notas de 100,')
      else:
        if cem == 5:
          print(f'cinco notas de 100,')
        else:
          if cem == 6:
            print(f'seis notas de 100,')
decimal = dinheiro//10%10
if decimal == 5:
  print('uma nota de 50,', end=' ')
else:
  if decimal > 5:
    nota_dez = decimal - 5
    if nota_dez == 1:
      print(f'uma nota de 50, uma nota de 10,', end=' ')
    else:
      if nota_dez == 2:
        print(f'uma nota de 50, duas notas de 10,', end=' ')
      else:
        if nota_dez == 3:
          print(f'uma nota de 50, três notas de 10,', end=' ')
        else:
          if nota_dez == 4:
            print(f'uma nota de 50, quatro notas de 10,', end=' ')
  else:
    if decimal == 1:
      print(f'uma nota de 10,', end=' ')
    else:
      if decimal == 2:
        print(f'duas notas de 10,', end=' ')
      else:
        if decimal == 3:
          print(f'três notas de 10,', end=' ')
        else:
          if decimal == 4:
            print(f'quatro notas de 10,', end=' ')
unidade = dinheiro//1%10
if unidade == 5:
  print('uma nota de 5,')
else:
  if unidade > 5:
    nota_um = unidade - 5
    if nota_um == 1:
      print(f'uma nota de 5, uma nota de 1.')
    else:
      if nota_um == 2:
        print(f'uma nota de 5, duas notas de 1.')
      else:
        if nota_um == 3:
          print(f'uma nota de 5, três notas de 1.')
        else:
          if nota_um == 4:
            print(f'uma nota de 5, quatro notas de 1.')
  else:
    if unidade == 1:
      print(f'uma nota de 1.')
    else:
      if unidade == 2:
        print(f'duas notas de 1.')
      else:
        if unidade == 3:
          print(f'três notas de 1.')
        else:
          if unidade == 4:
            print(f'quatro notas de 1.')
```





```python
#39ª Questão
numero = int(input('Digite um número inteiro:'))
if numero % 2 == 0:
  print('O número digitado é par.')
else:
  print('O número digitado é impar.')
```


```python
#40ª Questão
numero1 = float(input('Digite o primeiro número: '))
numero2 = float(input('Digite o segundo número: '))
operacao = input('informe qual operação você deseja realizar : ')
if operacao == 'soma':
  resultado = numero1 + numero2
else:
  if operacao == 'subtração':
    resultado = numero1 - numero2
  else:
    if operacao == 'multiplicação':
      resultado = numero1 * numero2
    else:
      if operacao == 'divisão':
        resultado = numero1 / numero2
      else:
        print('valor invalido')
print(f'O resultado é {resultado}')
if resultado % 2 == 0:
  print('O número digitado é par.')
else:
  print('O número digitado é impar.')
if resultado == 0:
  print('O numero informado é neutro. ')
else:
  if resultado > 0:
    print('O numero informado é positivo. ')
  if resultado < 0:
    print('O numero informado é negativo. ')
if resultado == int(resultado):
  print('inteiro')
else:
  print('decimal')
```





```python
#41ª Questão
print("Informe 1 para sim e 0 para não")
resp1 = int(input("Telefonou para a vítima? "))
resp2 = int(input("Esteve no local do crime? "))
resp3 = int(input("Mora perto da vítima? "))
resp4 = int(input("Devia para a vítima? "))
resp5 = int(input("Já trabalhou com a vítima? "))

soma_resp = resp1 + resp2 + resp3 + resp4 + resp5

if soma_resp == 2:
    print("Suspeita")
else:
    if soma_resp == 3 or soma_resp == 4:
        print("Cúmplice")
    else:
        if soma_resp == 5:
            print("Assassino")
        else:
            print("Inocente")
```





```python
#42ª Questão
tipo_combustivel = str(input('Tipo de combustivel [A/G] '))
litros = float(input('Quantos litros? '))
preco_g = 2.5*litros
preco_a = 1.9*litros
if tipo_combustivel in 'Aa':
  if litros <= 20:
    desconto = (preco_a * 0.03)
    print(f'O valor a ser pago será de R${preco_a-desconto:.2f}')
  else:
    desconto2 = (preco_a * 0.05)
    print(f'O valor a ser pago será de R${preco_a-desconto2:.2f}')
else:
  if tipo_combustivel in 'Gg':
    if litros <= 20:
      desconto = (preco_g * 0.04)
      print(f'O valor a ser pago será de R${preco_g-desconto:.2f}')
    else:
      desconto2 = (preco_g * 0.06)
      print(f'O valor a ser pago será de R${preco_g-desconto2:.2f}')
```





```python
#43ª Questão
morango = float(input('Quantidade em Kg de morango: '))
maca = float(input('Quantidade em Kg de maçã: '))
if morango <= 5:
  preco_morango = morango * 2.5
else:
  if morango > 5:
    preco_morango = morango * 2.2
if maca <= 5:
  preco_maca = maca * 1.8
else:
  if maca > 5:
    preco_maca = maca * 1.5
preco_total = preco_morango + preco_maca
if maca + morango > 8 or preco_total > 25:
  desconto = preco_total*0.9
  print(f'O valor a ser pago será de R${desconto:.2f}')
else:
  print(f'O valor a ser pago será de R${preco_total:.2f}')
```





```python
#44ª Questão
idade = int(input('Informe a idade do nadador: '))
if idade >= 5 and idade <= 7:
  print('Classificação: Infantil A')
else:
  if idade >= 8 and idade <= 10:
    print('Classificação: Infantil B')
  else:
    if idade >= 8 and idade <= 10:
      print('Classificação: Infantil B')
    else:
      if idade >= 11 and idade <= 13:
        print('Classificação: Juvenil A')
      else:
        if idade >= 14 and idade <= 17:
          print('Classificação: Juvenil B')
        else:
          if idade > 17:
            print('Classificação: Adulto')
          else:
            print('Sem classificação')
```



```python
#45ª Questão
altura = float(input('Altura: '))
sexo = input('Sexo [M/F]: ')
formula_m = (72.7*altura)-58
formula_f = (62.1*altura)-44.7
if sexo in 'Mm':
  print(f'Peso ideal: {formula_m:.1f}')
else:
  if sexo in 'Ff':
    print(f'Peso ideal: {formula_f:.1f}')
  else:
    print('Valor inválido')
```