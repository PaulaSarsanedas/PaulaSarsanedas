# Definir una lista de números
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Función para sumar todos los elementos de una lista
def suma_lista(lista):
    suma = 0
    for numero in lista:
        suma += numero
    return suma

# Llamar a la función para sumar los elementos de la lista 'numeros'
resultado = suma_lista(numeros)

print("La suma de los números en la lista es:", resultado)
