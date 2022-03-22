num = []
mayor = 0
casilla = 0

print("Ingresa 3 numeros")
for i in range(3):
    num1 = int(input("%d: " %(i + 1)))
    num.append(num1)
    if num[i] > mayor:
        mayor = num[i]

interruptor = 0
multiplicador = 0
multiplo = 0

while interruptor == 0:
    contador = 0
    multiplicador = multiplicador + 1
    multiplo = mayor * multiplicador
    for i in range(3):
        if multiplo % num[i] == 0:
            contador = contador + 1

    if contador == 3:
        interruptor = 1
print ("El M.C.M es: %d" %(multiplo))

MCM

numero1 = int(input("Número 1: "))
numero2 = int(input("Número 2: "))
numero3 = int(input("Número 3: "))
 
if numero1 < numero2 and numero1 < numero3:
    mcd = numero1
elif numero2 < numero1 and numero2 < numero3:
    mcd = numero2
else:
    mcd = numero3
while True:
    if numero1%mcd == 0 and numero2%mcd == 0 and numero3%mcd == 0:
        print("El mcd es", mcd)
        break
    else:
         mcd -= 1
         
 MCD
         
