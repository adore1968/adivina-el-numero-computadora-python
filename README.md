# Adivina el Número - La Computadora Adivina en Python

Este proyecto es una variante del juego clásico de "Adivina el Número", donde el jugador selecciona un número entre 1 y `x`, y la computadora intenta adivinarlo. El jugador da pistas a la computadora diciendo si la predicción es demasiado alta, baja o correcta, y la computadora ajusta su rango de predicción en consecuencia.

## Conceptos Utilizados

- **Funciones**: El juego está contenido en la función `adivina_el_numero_computadora(x)`, que acepta un parámetro `x` para definir el rango de números posibles.
- **Generación de Números Aleatorios**: La computadora genera una predicción aleatoria dentro de un rango definido usando `random.randint()`.
- **Ciclo `while`**: Se utiliza un bucle `while` para seguir adivinando hasta que la computadora adivine el número correctamente.
- **Condicionales**: Se emplean estructuras `if` y `elif` para ajustar el rango de predicción de la computadora basándose en las respuestas del jugador (alta, baja o correcta).
- **Entrada del Usuario**: Se usa `input()` para que el jugador ingrese la respuesta correspondiente ("A", "B" o "C").
