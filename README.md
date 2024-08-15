# Portugol-1
Meu Primeiro Repositório de Portugol

Algoritmo "questao1"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 14/08/2024
Var
 nome: caractere
Inicio
 
 escreval("Olá, qual o seu nome?")
 leia(nome)
 escreval("Olá, ", nome)

Fimalgoritmo
-------------------------------------------------------------
Algoritmo "questao2"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 14/08/2024
Var
 nome: caractere
 salario: real
Inicio
 
 escreval("Olá, qual o nome do(a) funcionário(a)?")
 leia(nome)
 escreval("Qual o salário dele(a)?")
 leia(salario)
 escreval("O nome do(a) funcionário(a) é ", nome, " e o salário dele(a) é de R$", salario, " reais!")

Fimalgoritmo
--------------------------------------------------------------------------------------------------------
Algoritmo "questao3"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 14/08/2024
Var
 valor1, valor2: inteiro
Inicio
 
 escreval("Digite o primeiro número")
 leia(valor1)
 escreval("Digite o segundo número")
 leia(valor2)
 escreval("O resultado da soma entre ", valor1, " e ", valor2, " é: ", valor1+valor2)

Fimalgoritmo
---------------------------------------------------------------------------------------
Algoritmo "questao4"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 14/08/2024
Var
 valor1, valor2: inteiro
Inicio
 
 escreval("Digite a primeira nota")
 leia(valor1)
 escreval("Digite a segunda nota")
 leia(valor2)
 escreval("O resultado da média entre ", valor1, " e ", valor2, " é: ", valor1+valor2%2)

Fimalgoritmo
-----------------------------------------------------------------------------------------
Algoritmo "questao5"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 14/08/2024
Var
 valor: inteiro
Inicio
 
 escreval("Digite um número")
 leia(valor)
 escreval("O antecessor de", valor," é ", valor-1)
 escreval("O sucessor de", valor," é ", valor+1)

Fimalgoritmo
------------------------------------------------------
Algoritmo "questao6"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 14/08/2024
Var
 valor: real
Inicio
 
 escreval("Digite um número")
 leia(valor)
 escreval("O dobro do número é ", valor*2)
 escreval("A terça parte do número é ", valor/3)
 

Fimalgoritmo
---------------------------------------------------------
Algoritmo "questao7"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 15/08/2024
Var
 valor: inteiro
Inicio

 escreval("Digite uma distancia em metros")
 leia(valor)
 escreval(valor,"m em km é de:", valor/1000,"km")
 escreval(valor,"m em hm é de:", valor/100,"hm")
 escreval(valor,"m em dam é de:", valor/10,"dam")
 escreval(valor,"m em dm é de:", valor/0.1,"dm")
 escreval(valor,"m em cm é de:", valor/0.01,"cm")
 escreval(valor,"m em mm é de:", valor/0.001,"mm")

Fimalgoritmo
------------------------------------------------------------
Algoritmo "questao8"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 15/08/2024
Var
 valor: real
Inicio

 escreval("Digite a quantidade de dinheiro que você tem na carteira em R$")
 leia(valor)
 escreval("Você pode comprar US$", valor/5.45)

Fimalgoritmo
-------------------------------------------------------------------------------
Algoritmo "questao9"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 15/08/2024
Var
 largura,altura: real
 litros: real
Inicio

 escreval("Digite a largura da parede")
 leia(largura)
 escreval("Digite a altura da parede")
 leia(altura)
 escreval("A área da parede é de:", largura*altura, "m²")
 escreval("A quantiadade de litros de tinta a ser utilizada na parede será de", largura*altura/2, "L")

Fimalgoritmo
-----------------------------------------------------------------------------------------------------------
Algoritmo "questao10"
// Disciplina   : [Laboratório de Programação]
// Descrição   : Primeira vez aprendendo Portugol
// Autor(a)    : Antônio Santiago
// Data atual  : 15/08/2024
Var
 dias,quilometragem: real
Inicio

 escreval("Digite a quantidade a Quilometragem rodada no carro alugado")
 leia(quilometragem)
 escreval("Digite a quantiadade de dias que o carro foi alugado")
 leia(dias)
 escreval("Custo de quilometragem: R$", quilometragem*0.20)
 escreval("Custo do aluguel: R$", dias*90)
 escreval("Total: R$", dias*90 + quilometragem*0.20)

Fimalgoritmo
