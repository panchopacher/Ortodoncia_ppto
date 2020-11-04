# Ortodoncia_ppto
Presupuesto de Ortodoncia
while True:		
	try: 		
		tpo_tto_estimado = int(input("El tiempo estimado de tratamiento en meses es de "))
		print("El tiempo estimado de tratamiento es de ", tpo_tto_estimado , " meses")
		print(" ")

		valor_anual_ort_Met_bi = int(input("El costo anual de tratamiento ortodontico bimaxilar con barckets metalicos es de $ "))

		valor_anual_ort_Est_bi = int(float(valor_anual_ort_Met_bi*1.3))

		break

	except ValueError:
		print("El valor introducido no es correcto. Vuelva a ingresarlo")

print("El costo anual de tratamiento ortodontico bimaxilar con barckets Estetico es de $ ", valor_anual_ort_Est_bi)

costo_mensual_ort_met= (valor_anual_ort_Met_bi/12)
costo_mensual_ort_est = (valor_anual_ort_Est_bi/12)

monomaxilarMetal=int(float(valor_anual_ort_Met_bi*1.20)/2)
monomaxilarEst = int(float(monomaxilarMetal*1.3))

"""print ("El costo anual de tratamiento monomaxilar barckets metalicos es de $ ", monomaxilarMetal)
print ("El costo anual de tratamiento monomaxilar barckets esteticos es de $ ", monomaxilarEst)"""

# ---------------------- FINANCIACION --------------------------------------------------------------

print(" ")
print(" ")
print("FORMA DE PAGO")
print(" ")
print(" ")

costo_total_tto_metal= int(float(costo_mensual_ort_met*tpo_tto_estimado))
print("El costo total del tratamiento de ortodoncia METALICO indicado para el paciente es de $ ", costo_total_tto_metal)

costo_total_tto_est=int(float(costo_mensual_ort_est*tpo_tto_estimado))
print("El costo total del tratamiento de ortodoncia ESTETICO indicado para el paciente es de $ ", costo_total_tto_est)

# ---------------------- ORTODONCIA METALICA --------------------------------------------------------------

print(" ")
print("------------------------------------")
print("FINANCIANCION DE ORTODONCIA METALICA")
print("------------------------------------")

print(" ")
print("Forma de pago 1")


valor1= costo_total_tto_metal*0.9
valor2= costo_total_tto_metal/2
valor3= (costo_total_tto_metal*1.05)/3

valor6= (costo_total_tto_metal*1.20)/6
valor9= (costo_total_tto_est*1.35)/9

valor_107=(costo_total_tto_metal/2)
valor_207= int((valor_107 * 1.15)/6)
valor_307 = int((valor_207 * 1.23))

valor_118= (costo_total_tto_metal/3)
valor_618 = int((valor_118 *1.15 )/6)
valor_1218 = int(valor_618 * 1.20)
valor_1818 = int(valor_1218 *1.25)


cuota1= int(valor1)
print("El valor del tratamiento en 1 (una) cuota al inicio del tratamiento es de $", str(cuota1))

cuota2= int(valor2)
print("El valor del tratamiento en 2 (dos) cuotas mensuales es de $", str(cuota2))

cuota3= int(valor3)
print("El valor del tratamiento en 3 (tres) cuotas mensuales es de $", str(cuota3))

cuota6= int(valor6)
print("El valor del tratamiento en 6 (seis) cuotas mensuales es de $", str(cuota6))


cuota9= int(valor9)
print("El valor del tratamiento en 9 (nueve) cuotas mensuales es de $", str(cuota9))

cuota12= int(valor_107)
print("El valor del tratamiento en 12 (doce) cuotas mensuales. Las primeras seis (6) cuotas son de $", str(valor_207))
print("Las segundas seis (6) cuotas son de $", str(valor_307))


cuota18= int(valor_118)
print("El valor del tratamiento en 18 (dieciocho) cuotas mensuales. Las primeras seis (6) cuotas son de $", str(valor_618))
print("Las segundas seis (6) cuotas son de $", str(valor_1218))
print("Las terceras seis (6) cuotas son de $", str(valor_1818))


# ---------------------- ORTODONCIA ESTETICA-----------------------------------------------------


print(" ")
print("------------------------------------")
print("FINANCIANCION DE ORTODONCIA ESTETICA")
print("------------------------------------")
print("          FORMA DE PAGO 1")
print(" ")

valor1a= costo_total_tto_est*0.9
valor2a= costo_total_tto_est/2
valor3a= (costo_total_tto_est*1.05)/3

valor6a= (costo_total_tto_est*1.20)/6

valor9a= (costo_total_tto_est*1.35)/6

valor_107a=(costo_total_tto_est/2)
valor_207a= int((valor_107a * 1.15)/6)
valor_307a = int((valor_207a * 1.23))

valor_118a= (costo_total_tto_est/3)
valor_618a = int((valor_118a *1.15 )/6)
valor_1218a = int(valor_618a * 1.20)
valor_1818a = int(valor_1218a *1.25)




cuota1a= int(valor1a)
print("El valor del tratamiento en 1 (una) cuota al inicio del tratamiento es de $", str(cuota1a))

cuota2a= int(valor2a)
print("El valor del tratamiento en 2 (dos) cuotas mensuales es de $", str(cuota2a))

cuota3a= int(valor3a)
print("El valor del tratamiento en 3 (tres) cuotas mensuales es de $", str(cuota3a))

cuota6a= int(valor6a)
print("El valor del tratamiento en 6 (seis) cuotas mensuales es de $", str(cuota6a))

print(" ")

cuota9a= int(valor9a)
print("El valor del tratamiento en 9 (nueve) cuotas mensuales es de $", str(cuota9a))

print(" ")

cuota12a= int(valor_107a)
print("El valor del tratamiento en 12 (doce) cuotas mensuales. Las primeras seis (6) cuotas son de $", str(valor_207a))
print("Las segundas seis (6) cuotas son de $", str(valor_307a))

print(" ")

cuota18a= int(valor_118a)
print("El valor del tratamiento en 18 (dieciocho) cuotas mensuales. Las primeras seis (6) cuotas son de $", str(valor_618a))
print("Las segundas seis (6) cuotas son de $", str(valor_1218a))
print("Las terceras seis (6) cuotas son de $", str(valor_1818a))


print(" ")


print("FORMA DE PAGO CON ENTREGA INICIAL - ORTODONCIA METALICA")

print(" ")

entregar= int(input("Indique la cantidad de entrega inicial para Ortodoncia Metalica: "))
entrega=entregar
resto_metal= costo_total_tto_metal - entrega
financiar6= resto_metal* 1.2 /6
financiar9= resto_metal * 1.35/9
financiar12= resto_metal * 1.50/12

print(" ")
print(" ")

print("Entrega inicial de $",entrega)
print(" ")

cuota_seis= int(float(financiar6))
print("El resto en seis (6) cuotas de $",str(cuota_seis))

cuota_nueve= int(float(financiar9))
print("El resto en nueve (9) cuotas de $",str(cuota_nueve))

cuota_doce= int(float(financiar12))
print("El resto en doce (12) cuotas de $",str(cuota_doce))


print(" ")
print(" ")

print("FORMA PAGO  CON ENTREGA INICIAL - ORTODONCIA ESTETICA")
print(" ")

print(" ")

entregar_1= int(input("Indique la cantidad de entrega inicial para Ortodoncia Estetica: "))
entrega_1=entregar_1
resto_estetico= costo_total_tto_est - entrega_1
financiar6= resto_estetico* 1.20 /6

financiar9= resto_estetico * 1.35/9

financiar12= resto_estetico * 1.50/12
print(" ")
print(" ")

print("Entrega inicial de $",entrega_1)
print(" ")

cuota_seis= int(float(financiar6))
print("El resto en seis (6) cuotas de $ ",str(cuota_seis))

cuota_nueve= int(float(financiar9))
print("El resto en nueve (9) cuotas de $ ",str(cuota_nueve))

cuota_doce= int(float(financiar12))
print("El resto en doce (12) cuotas de $ ",str(cuota_doce))
