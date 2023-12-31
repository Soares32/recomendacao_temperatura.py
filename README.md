# recomendacao_temperatura.py

temperatura : float 

# Obtém a temperatura do usuário como entrada
temperatura = float(input("Digite a temperatura em graus Celsius: "))

# Verifica a faixa de temperatura usando if, elif e else

if temperatura < 0 :
  print("Está muito frio lá fora. Vista-se muito bem!")
elif 0 <= temperatura <= 20:
  print("A temperatura está moderada. Vista-se adequadamente.")
elif  20 < temperatura <= 30:
  print("Está um pouco quente. Considere usar roupas leves.")
else: 
  print("Está muito quente lá fora. Tome precauções para evitar o calor excessivo.")

