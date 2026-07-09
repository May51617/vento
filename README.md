# pedir a velocidade do vento
vento = int (input('Qual a velocidade do vento neste momento?'))
status = None

# retornar status do tempo
if vento < 7:
  status = 'Calmaria'
elif vento <= 8 and vento >= 35:
  status = 'Brisa'
elif vento <= 36 and vento >= 62:
  status = 'Vento Forte'
elif vento <= 63 and vento >= 74:
  status = 'Ventania'
else:
  status = 'Tempestade'

# mostrar o resultado
print (f'{status}')
