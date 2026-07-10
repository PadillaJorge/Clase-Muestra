## La Sentencia `if` (Ejecución Condicional)

La sentencia `if` es el motor de la toma de decisiones en Python. Evalúa una condición y, si es verdadera, ejecuta un bloque de código específico. Su estructura formal es:

> **`if`** condición_a_evaluar **`:`** bloque_de_código
> **`elif`** otra_condición **`:`** bloque_de_código
> **`else`** **`:`** bloque_de_respaldo

###  Ejemplo Práctico: El Cadenero Virtual

Imagina el filtro de entrada de un antro. La computadora evalúa la edad exacta del cliente antes de decidir qué camino tomar.

```python
# El Cadenero Virtual del Hart
edad_cliente = int(input("Ingrese su edad: "))
edad_minima = 18

if edad_cliente >= edad_minima:
    print("Acceso concedido. Bienvenido al Hart.")
else:
    print("Acceso denegado. Rumbo al Parque de la Selva 🦕")

```

## Comparadores (Operadores Relacionales)
Son las herramientas que usamos para comparar dos valores. El resultado de esta comparación siempre será un valor booleano: `True` (Verdadero) o `False` (Falso).

* **`==` (Igual a):** Verifica si dos valores son idénticos. *(Ojo: un solo `=` sirve para asignar variables; dos `==` sirven para comparar).*
* **`!=` (Diferente de):** Verifica si los valores son distintos.
* **`>` (Mayor que) / `<` (Menor que):** Evalúa quién es más grande.
* **`>=` (Mayor o igual) / `<=` (Menor o igual):** Incluye el límite en la comparación (como en el ejemplo de la edad).

## Operadores Lógicos (Decisiones Compuestas)
Cuando el cadenero necesita evaluar más de una regla al mismo tiempo, usamos los operadores lógicos para unir comparaciones.

* **`and` (Y):** Exigente. **Todas** las condiciones deben ser verdaderas para pasar.
* **`or` (O):** Flexible. Con que **una sola** condición sea verdadera, es suficiente.
* **`not` (NO):** Inversor. Cambia `True` por `False` y viceversa. Excelente para detectar errores rápido.