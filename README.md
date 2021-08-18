# exercicio_19

#shufflying elements of a group

from random import shuffle
pri = str ( input ('primeiro aluno: '))
seg = str ( input ('segundo aluno: '))
ter = str ( input ('terceiro aluno: '))
qua = str ( input ('quarto aluno: '))
grp = [pri , seg , ter , qua]
shuffle (grp)
print ('a ordem de apresentacao sera')
print (grp)

