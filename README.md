# pair-carla
Pair Program
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**Ejericios bucles for**\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. Imprimir los números del 1 al 5 utilizando un bucle for\n",
    "Descripción: Utiliza un bucle for para imprimir los números del 1 al 5 (incluido) en orden ascendente."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "for i in range(1,6):\n",
    "    print(i)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2. Calcular la suma de los primeros 10 números naturales utilizando un bucle for\n",
    "Descripción: Utiliza un bucle for para calcular la suma de los primeros 10 números naturales (1 + 2 + 3 + ... + 10)."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "55\n"
     ]
    }
   ],
   "source": [
    "suma = 0\n",
    "\n",
    "for i in range(1,11):\n",
    "    suma = suma + i\n",
    "print(suma)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3. Calcular el producto de los elementos de una lista\n",
    "Descripción: Dada una lista de números, utiliza un bucle for para calcular el producto de todos los elementos."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "16\n"
     ]
    }
   ],
   "source": [
    "lista = [1, 2, 3, 4]\n",
    "\n",
    "for i in range(len(lista)):\n",
    "    producto = lista[i] * lista[i]\n",
    "print(producto)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "4. Imprimir los caracteres de una cadena de texto\n",
    "Descripción: Dada una cadena de texto, utiliza un bucle for para imprimir cada carácter en una línea separada."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "H\n",
      "o\n",
      "l\n",
      "a\n"
     ]
    }
   ],
   "source": [
    "cadena = \"Hola\"\n",
    "\n",
    "for letra in cadena:\n",
    "    print(letra)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "5. Imprimir los números pares del 1 al 100 utilizando un bucle for\n",
    "Descripción: Utiliza un bucle for para imprimir los números pares del 1 al 100 en orden ascendente."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2\n",
      "4\n",
      "6\n",
      "8\n",
      "10\n",
      "12\n",
      "14\n",
      "16\n",
      "18\n",
      "20\n",
      "22\n",
      "24\n",
      "26\n",
      "28\n",
      "30\n",
      "32\n",
      "34\n",
      "36\n",
      "38\n",
      "40\n",
      "42\n",
      "44\n",
      "46\n",
      "48\n",
      "50\n",
      "52\n",
      "54\n",
      "56\n",
      "58\n",
      "60\n",
      "62\n",
      "64\n",
      "66\n",
      "68\n",
      "70\n",
      "72\n",
      "74\n",
      "76\n",
      "78\n",
      "80\n",
      "82\n",
      "84\n",
      "86\n",
      "88\n",
      "90\n",
      "92\n",
      "94\n",
      "96\n",
      "98\n",
      "100\n"
     ]
    }
   ],
   "source": [
    "for i in range(1,101):\n",
    "    if i % 2 == 0:\n",
    "        print(i)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "6. Imprimir los números primos del 1 al 50 utilizando un bucle for\n",
    "Descripción: Utiliza un bucle for para imprimir los números primos del 1 al 50 en orden ascendente.\n",
    "- NOTA: Según la Wikipedia, un número primo es un número natural mayor que 1 que no tiene divisores positivos más que 1 y él mismo."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2\n",
      "3\n",
      "5\n",
      "7\n",
      "11\n",
      "13\n",
      "17\n",
      "19\n",
      "23\n",
      "29\n",
      "31\n",
      "37\n",
      "41\n",
      "43\n",
      "47\n"
     ]
    }
   ],
   "source": [
    "for i in range(2,51):\n",
    "    es_primo = True\n",
    "    for e in range(2, i):\n",
    "        if i % e == 0:\n",
    "            es_primo = False\n",
    "    if es_primo:\n",
    "        print(i)\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "7. Calcular el factorial de un número utilizando un bucle for\n",
    "Descripción: Dado un número entero positivo, calcula su factorial utilizando un bucle for."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "5040\n"
     ]
    }
   ],
   "source": [
    "numero = 7\n",
    "factorial = 1\n",
    "\n",
    "for i in range(1, numero + 1):\n",
    "   factorial = factorial * i\n",
    "\n",
    "print(factorial)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "8. Juego de adivinar palabras utilizando un bucle for\n",
    "Descripción: Crea un juego en el que el jugador debe adivinar una palabra secreta. El jugador tiene un número limitado de intentos y se le proporcionan pistas después de cada intento. Utiliza un bucle for para controlar los intentos del jugador."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**CON BUCLE WHILE**"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "No has acertado, aqui va una pista, la siguiente letra es H\n",
      "No has acertado, aqui va una pista, la siguiente letra es o\n",
      "No has acertado, aqui va una pista, la siguiente letra es l\n",
      "Enhorabuena, has acertado, la palabra era Hola\n"
     ]
    }
   ],
   "source": [
    "palabra_secreta = \"Hola\"\n",
    "\n",
    "intentos = len(palabra_secreta)\n",
    "count = 0\n",
    "while intentos > 0:\n",
    "    respuesta = input(\"Adivina la palabra\")\n",
    "    if respuesta == palabra_secreta:\n",
    "        print(\"Enhorabuena, has acertado, la palabra era\", palabra_secreta)\n",
    "        intentos = 0\n",
    "    else:\n",
    "        intentos -= 1\n",
    "        print(\"No has acertado, aqui va una pista, la siguiente letra es\", palabra_secreta[count])\n",
    "        count += 1    "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**CON BUCLE FOR**"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "No has acertado, aqui va una pista, la siguiente letra es H\n",
      "Te quedan 3 intentos\n",
      "No has acertado, aqui va una pista, la siguiente letra es o\n",
      "Te quedan 2 intentos\n",
      "No has acertado, aqui va una pista, la siguiente letra es l\n",
      "Te quedan 1 intentos\n",
      "Enhorabuena, has acertado, la palabra era Hola\n"
     ]
    }
   ],
   "source": [
    "palabra_secreta = \"Hola\"\n",
    "\n",
    "intentos = len(palabra_secreta)\n",
    "count = 0\n",
    "\n",
    "for i in list(palabra_secreta):\n",
    "    respuesta = input(\"Adivina la palabra\")\n",
    "    if respuesta == palabra_secreta:\n",
    "        print(\"Enhorabuena, has acertado, la palabra era\", palabra_secreta)\n",
    "        \n",
    "    else:\n",
    "        intentos -= 1\n",
    "        print(\"No has acertado, aqui va una pista, la siguiente letra es\", palabra_secreta[count])\n",
    "        print(f\"Te quedan {intentos} intentos\")\n",
    "        count += 1   \n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# List comprehension"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. Generar una lista de los números pares del 1 al 20.\n",
    "Descripción: Utiliza list comprehension para generar una lista que contenga todos los números pares en el rango del 1 al 20."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[2, 4, 6, 8, 10, 12, 14, 16, 18, 20]\n"
     ]
    }
   ],
   "source": [
    "numeros = [num for num in range(1,21) if num % 2 ==0]\n",
    "print(numeros)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "2. Obtener una lista de las vocales en una cadena de texto.\n",
    "Descripción: Utiliza list comprehension para crear una lista que contenga todas las vocales presentes en una cadena de texto (sin repetición)."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['o', 'a', 'u', 'e', 'a']\n"
     ]
    }
   ],
   "source": [
    "vocales = [l for l in \"Hola que tal\" if l in [\"a\", \"e\", \"i\", \"o\", \"u\"]]\n",
    "print(vocales)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "3. Filtrar los números positivos de una lista y calcular su cuadrado.\n",
    "Descripción: Utiliza list comprehension para filtrar los números positivos de una lista y calcular el cuadrado de cada uno."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[0, 1, 4, 9, 16]\n"
     ]
    }
   ],
   "source": [
    "cuadrado = [num ** 2 for num in range(-5,5) if num >= 0]\n",
    "print(cuadrado)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Try ... except"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "1. Realizar una búsqueda en una lista y capturar una excepción en caso de valor no encontrado.\n",
    "Descripción: Solicita al usuario una lista de nombres y un nombre para buscar en la lista. Intenta encontrar el nombre en la lista y utiliza las sentencias try y except para capturar la excepción en caso de que el nombre no sea encontrado."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "ename": "IndentationError",
     "evalue": "unexpected indent (2090148140.py, line 6)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"/tmp/ipykernel_25808/2090148140.py\"\u001b[0;36m, line \u001b[0;32m6\u001b[0m\n\u001b[0;31m    if buscar in lista_nombres:\u001b[0m\n\u001b[0m    ^\u001b[0m\n\u001b[0;31mIndentationError\u001b[0m\u001b[0;31m:\u001b[0m unexpected indent\n"
     ]
    }
   ],
   "source": [
    "lista_nombres = list(input(\"Introduzca los nombres separados por coma\"))\n",
    "print(lista_nombres)\n",
    "buscar = input(\"Escriba el nombre que quiere buscar\")\n",
    "\n",
    "try:\n",
    "    if buscar in lista_nombres:\n",
    "          print(\"El nombre esta en la lista\")\n",
    "except:\n",
    "        print(\"El nombre no esta en la lista\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['Ana', 'Celia', 'Sara']\n"
     ]
    }
   ],
   "source": [
    "lista_nombres = input(\"Introduzca los nombres separados por coma\")\n",
    "print(lista_nombres.split(\",\"))\n",
    "buscar = input(\"Escriba el nombre que quiere buscar\")\n",
    "\n",
    "if buscar in lista_nombres.split(\",\"):\n",
    "          print(\"El nombre esta en la lista\")\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "base",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
