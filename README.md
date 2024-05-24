Algoritmo "Media"

Var
n1,n2,n3,n4,med:real

Inicio
Escreval("digite a nota 1")
Leia(n1)
Escreval("digite a nota 2")
Leia (n2)
Escreval("digite a nota 3")
Leia (n3)
Escreval("digite a nota 4")
Leia (n4)


med:=(n1+n2+n3+n4)/4

Escreval("A media final do aluno é´",med)

  se(med<3) entao
    escreval ("Aluno reprovado")
fimse
  se(med >=3)e(med <= 7) entao
  escreval ("Aluno de recuperação")
fimse
  se (med>7) entao
  escreval ("Aluno aprovado")
fimse


Fimalgoritmo
