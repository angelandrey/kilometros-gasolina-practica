# kilometros-gasolina-practica
print(" ")
print("Angel Andrey Muñoz Centeno 3W")
print(" ")
# Solicitar al usuario la cantidad de kilómetros recorridos
kilometros = float(input("Ingrese la cantidad de kilómetros recorridos: "))

# Solicitar al usuario la cantidad de litros de combustible consumidos
litros = float(input("Ingrese la cantidad de litros de combustible consumidos: "))

# Calcular el consumo de combustible por kilómetro
if kilometros > 0:
    consumo_por_km = litros / kilometros
    print(f"El consumo de combustible es de {consumo_por_km:.2f} litros por kilómetro.")
else:
    print("La cantidad de kilómetros debe ser mayor que cero.")
![image](https://github.com/user-attachments/assets/eb6a9d20-d8b2-4359-a6e5-d1db1789f2e1)
