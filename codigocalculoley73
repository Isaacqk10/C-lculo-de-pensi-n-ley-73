#Calculo de pensión ley 73 o modalidad 40 del IMSS.#
#Estimación propia con metodología de calculo de pensión IMSS.#
#Dónde la fórmula para el cálculo de la misma se expresa a través de la siguiente formula:
    #SBC{[CB+(IA*EXC)]}*1.11
    # Siendo las variables:
        #SBC: Salario base de cotización
        #CB: Cuantía básica
        #IA: Incremento anual
        #EXC: Excedente de semanas cotizadas.
SC = float(input("Ingresa el total de tus semanas cotizadas:\n"))
AGE = int(input("Ingresa tu edad actual:\n"))
SBC = float(input("Ingresa el salario promedio al mes de tus últimos 5 años laborados y registrados en el IMSS:\n" ))
EXC = (SC+3328-(AGE*52)-500)/52
CB = SBC/3300.53
EDAD = int(input("Ingresa tu edad de retiro a partir de los 60 años:\n"))
POR = ""
if EDAD <= 60:
    POR = float(0.75)
if EDAD == 61:
    POR = float(0.80)
if EDAD <= 62:
    POR = float(0.85)
if EDAD <= 63:
    POR = float(0.90)
if EDAD <= 64:
    POR = float(0.95)
if EDAD >= 65:
    POR = float(0.75)
IA1 = POR*(SBC*(0.80+(0.00563*EXC)*1.11))
IA101 = POR*(SBC*(0.7711+(0.00814*EXC)*1.11))
IA126 = POR*(SBC*(0.5818+(0.01178*EXC)*1.11))
IA151 = POR*(SBC*(0.4923+(0.01430*EXC)*1.11))
IA176 = POR*(SBC*(0.4267+(0.01615*EXC)*1.11))
IA201 = POR*(SBC*(0.3765+(0.01756*EXC)*1.11))
IA226 = POR*(SBC*(0.3368+(0.01868*EXC)*1.11))
IA251 = POR*(SBC*(0.3048+(0.01958*EXC)*1.11))
IA276 = POR*(SBC*(0.2783+(0.02033*EXC)*1.11))
IA301 = POR*(SBC*(0.2560+(0.02096*EXC)*1.11))
IA326 = POR*(SBC*(0.2370+(0.02149*EXC)*1.11))
IA351 = POR*(SBC*(0.2207+(0.02195*EXC)*1.11))
IA376 = POR*(SBC*(0.2065+(0.02235*EXC)*1.11))
IA401 = POR*(SBC*(0.1939+(0.02271*EXC)*1.11))
IA426 = POR*(SBC*(0.1829+(0.02302*EXC)*1.11))
IA451 = POR*(SBC*(0.1730+(0.02330*EXC)*1.11))
IA476 = POR*(SBC*(0.1641+(0.02355*EXC)*1.11))
IA501 = POR*(SBC*(0.1561+(0.02377*EXC)*1.11))
IA526 = POR*(SBC*(0.1488+(0.02398*EXC)*1.11))
IA551 = POR*(SBC*(0.1422+(0.02416*EXC)*1.11))
IA576 = POR*(SBC*(0.1362+(0.02433*EXC)*1.11))
IA601 = POR*(SBC*(0.1300+(0.02450*EXC)*1.11))
if CB <= 1:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA1:.2f}")
if 1.01 <= CB <= 1.2599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA101:.2f}")
if 1.26 <= CB <= 1.5099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA126:.2f}")
if 1.51 <= CB <= 1.7599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA151:.2f}")
if 1.76 <= CB <= 2.099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA176:.2f}")
if 2.01 <= CB <= 2.2599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA201:.2f}")
if 2.26 <= CB <= 2.5099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA226:.2f}")
if 2.51 <= CB <= 2.7599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA251:.2f}")
if 2.76 <= CB <= 3.099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA276:.2f}")
if 3.01 <= CB <= 3.2599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA301:.2f}")
if 3.26 <= CB <= 3.5099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA326:.2f}")
if 3.51 <= CB <= 3.7599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA351:.2f}")
if 3.76 <= CB <= 4.099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA376:.2f}")
if 4.01 <= CB <= 4.2599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA401:.2f}")
if 4.26 <= CB <= 4.5099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA426:.2f}")
if 4.51 <= CB <= 4.7599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA451:.2f}")
if 4.76 <= CB <= 5.099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA476:.2f}")
if 5.01 <= CB <= 5.2599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA501:.2f}")
if 5.26 <= CB <= 5.599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA526:.2f}")
if 5.51 <= CB <= 5.7599:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA551:.2f}")
if 5.76 <= CB <= 6.099:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA576:.2f}")
if CB >= 6.01:
  print(f"El monto de tu pensión a los {EDAD} años es de:\n${IA601:.2f}")
