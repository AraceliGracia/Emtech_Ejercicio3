# Emtech_Ejercicio3

NumCostalesYeso=input("Ingrese la cantidad de costales de Yeso que desea: ")

NumCostalesCemento=input("Ingrese la cantidad de costales de Cemento que desea: ")

pesoTotalYeso=(int(NumCostalesYeso)*int(30))
pesoTotalCemento=(int(NumCostalesCemento) *int(40))
print("El total del peso es: ")
pesoTotal=int(pesoTotalYeso)+int(pesoTotalCemento)
print(pesoTotal)

if int(pesoTotal)>int(3254) and int(pesoTotal)<int(1627):
  print("Autorizacion del envio:TRUE")
else:
  print("Autorizacion del envio:FALSE")
  







