# DevMetaWeb

Algoritmo "Atividade 04 - 25"
Var
a,b: real
Inicio
escreval("Digite um numero:")
leia(a)
escreval("Digite um numero:")
leia(b)
se (a = b) entao
   escreva("Digite um valor diferente.")
senao
   se (a > b) entao
      escreva("O maior valor é ",a)
   senao
        escreva("O maior valor é ",b)
   fimse
fimse
Fimalgoritmo

##################################################

Algoritmo "Atividade 04 - 26"
Var
n: real
Inicio
escreval("Digite um numero:")
leia(n)
se (n <= 10) entao
   escreva("F1")
fimse
se (n > 10) e (n <= 100) entao
   escreva("F2")
fimse
se (n > 100) entao
   escreva("F3")
fimse
Fimalgoritmo

#################################################

Algoritmo "Atividade 04 - 27"
Var
nU, nD, nT, media: real
Inicio
escreval("Digite a nota da 1 prova: ")
leia(nU)
escreval("Digite a nota da 2 prova: ")
leia(nD)
escreval("Digite a nota da 3 prova: ")
leia(nT)
media <- (nU*2 + nD*3 + nT*5)/3
escreva("a media foi ",media)
Fimalgoritmo

###################################################

Algoritmo "Atividade 04 - 28"
Var
vU, vD, vT: real
Inicio
escreval("Digite o valor 1: ")
leia(vU)
escreval("Digite o valor 2: ")
leia(vD)
escreval("Digite o valor 3: ")
leia(vT)
se (vU = vT) ou (vU = vT) ou (vD = vU) ou (vD = vT) entao
   escreva("Digite valores diferentes.")
senao
   se (vU < vD) e (vU < vT) e (vD < vT) entao
      escreval(vU," (valor 1) < ",vD," (valor 2) < ",vT," (valor 3)")
   fimse
   se (vD < vU) e (vD < vT) e (vU < vT) entao
      escreval(vD," (valor 2) < ",vU," (valor 1) < ",vT," (valor 3)")
   fimse
   se (vT < vU) e (vT < vD) e (vD < vU) entao
      escreval(vT," (valor 3) < ",vD," (valor 2) < ",vU," (valor 1)")
   fimse
   se (vU < vD) e (vU < vT) e (vT < vD) entao
      escreva(vT," (valor 1) < ",vD," (valor 3) < ",vU," (valor 2)")
   fimse
   se (vD < vT) e (vD < vU) e (vT < vU) entao
      escreval(vD," (valor 2) < ",vT," (valor 3) < ",vU," (valor 1)")
   fimse
fimse
Fimalgoritmo

###########################################################

Algoritmo "Atividade 04 - 29"
Var
nome: caractere
notaP, notaM, notaC, media: real
Inicio
escreval("Digite seu nome:")
leia(nome)
escreval("Digite a nota de português:")
leia(notaP)
escreval("Digite a nota de matemática:")
leia(notaM)
escreval("Digite a nota de conhecimentos gerais:")
leia(notaC)
escreval(nome)
escreval("sua nota em português foi ",notaP)
escreval("sua nota em matemática foi ",notaM)
escreval("sua nota em conhecimentos gerais foi ",notaC)
media <- (notaP + notaM + notaC)/3
escreval("sua media foi ",media)
se (media > 7 ) e (notaP > 5) e (notaM > 5) e (notaC > 5) entao
   escreval(nome," você foi aprovado.")
senao
     escreval(nome," você foi reprovado")
fimse
Fimalgoritmo

############################################################
