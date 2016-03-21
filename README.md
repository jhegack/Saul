c = int(input("ingrese la cantidad de clientes que ingresaron: "))
totalc = 0
#for para preguntar a los clientes la cantidad de compra
for i in range(c):
	print (i,"° cliente")
	Costo = int(input("indique el costo de la compra: s/."))
	totalc = totalc+Costo
#imprimir el resultado
print ("la venta total del dia es S/.",totalc)
