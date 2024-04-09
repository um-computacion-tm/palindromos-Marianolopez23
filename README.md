# Alumno: Mariano Lopez
Ingenieria Informatica
### Palabras Palindromas
    def is_palindrome(value):
        # Muestra el valor recibido en la función
        print(value)
        # Muestra el valor invertido [::-1]
        print(value[::-1])
        # Compara el valor original con el valor invertido
        if value == value[::-1]:
            # Si son iguales, devuelve True
            return True
        else:
        # Si no son iguales, devuelve False
        return False

## Para comprobar si funciona

    -Realizar un git clone (link con el SSH del repo) en la carpeta donde querras guardar el programa.
    -Una vez con los direcctorios en su computadora los busca en la terminal usando cd (nombre de la carpeta donde se encuentra el archivo)
    -Ya en la carpeta donde se encuentra el archivo ejecutamos python3 test_palindromos.py
    -Luego de esto y finalmente se ejecutaran los test para comprobar si los codigos funcionan correctamete.

### Contador de Palabras Palindromas
    def cantidad_de_palabras_palindromes(palabras):
        # Inicializa un contador para llevar la cuenta de palabras palíndromas
        contador = 0
        # Itera sobre cada palabra en la lista de palabras
        for palabra in palabras:
            # Limpia la palabra eliminando espacios, comas y guiones, y la convierte a minúsculas
            palabra = palabra.replace(" ","").replace(",","").replace("-","").lower()
            # Comprueba si la palabra es un palíndromo comparándola con su inversa
            if palabra == palabra[::-1]:
              # Si la palabra es un palíndromo, incrementa el contador en 1
                contador += 1
        # Devuelve la cantidad total de palabras palíndromas encontradas
        return contador

## Para comprobar si funciona

    -Realizar un git clone (link con el SSH del repo) en la carpeta donde querras guardar el programa.
    -Una vez con los direcctorios en su computadora los busca en la terminal usando cd (nombre de la carpeta donde se encuentra el archivo)
    -Ya en la carpeta donde se encuentra el archivo ejecutamos python3 test_contador_palindromos.py
    -Luego de esto y finalmente se ejecutaran los test para comprobar si los codigos funcionan correctamete.