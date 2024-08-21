
# Soluciones a los Ejercicios Prácticos con Funciones Lambda en Python

## Problema 1: Doblar los Números
Dada una lista de números, escribe una función lambda que duplique cada número en la lista.

**Entrada:**
```python
numeros = [1, 2, 3, 4, 5]
```

**Solución:**
```python
resultado = list(map(lambda x: x * 2, numeros))
print(resultado)
```

**Salida esperada:**
```python
[2, 4, 6, 8, 10]
```

## Problema 2: Filtrar Palabras Largas
Escribe una función lambda que filtre las palabras de una lista que tengan más de 5 letras.

**Entrada:**
```python
palabras = ["perro", "gato", "elefante", "oso", "jirafa"]
```

**Solución:**
```python
resultado = list(filter(lambda x: len(x) > 5, palabras))
print(resultado)
```

**Salida esperada:**
```python
["elefante", "jirafa"]
```

## Problema 3: Ordenar una Lista de Tuplas
Dada una lista de tuplas, cada una representando un punto en un plano (x, y), escribe una función lambda que ordene la lista según la distancia de cada punto al origen (0, 0).

**Entrada:**
```python
puntos = [(1, 2), (2, 3), (0, 1), (3, 3)]
```

**Solución:**
```python
resultado = sorted(puntos, key=lambda punto: (punto[0]**2 + punto[1]**2)**0.5)
print(resultado)
```

**Salida esperada:**
```python
[(0, 1), (1, 2), (2, 3), (3, 3)]
```

## Problema 4: Elevar al Cuadrado
Escribe una función lambda que eleve al cuadrado cada número en una lista dada.

**Entrada:**
```python
numeros = [2, 4, 6, 8, 10]
```

**Solución:**
```python
resultado = list(map(lambda x: x**2, numeros))
print(resultado)
```

**Salida esperada:**
```python
[4, 16, 36, 64, 100]
```

## Problema 5: Filtrar Números Impares
Escribe una función lambda que filtre los números impares de una lista dada.

**Entrada:**
```python
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```

**Solución:**
```python
resultado = list(filter(lambda x: x % 2 != 0, numeros))
print(resultado)
```

**Salida esperada:**
```python
[1, 3, 5, 7, 9]
```

Estas soluciones demuestran cómo se pueden utilizar las funciones lambda para resolver problemas comunes en Python. ¡Espero que te sean útiles!
