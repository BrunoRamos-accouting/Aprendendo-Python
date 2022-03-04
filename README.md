# Aprendendo-Python

#Desafio 2 - Calculadora de tinta

rend = int(input('Qual a rendimento da lata? '))
altura = int(input('Qual a altura da parede? '))
largura = int(input('Qual a largura da parede? '))


def quant_latas():
   x =  (largura * altura) / rend
   print (f'Você precisa de {x} latas para pintar a parede')
    
quant_latas()
