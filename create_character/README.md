# Crear un personaje de RPG (Python)

Ejercicio del curso **"Learn Python by Building a Role Playing Game"** de freeCodeCamp.

## Descripción

Programa que define una función `create_character` para generar un personaje de rol.
La función valida:

- Que el nombre sea una cadena de texto, no vacía, de máximo 10 caracteres y sin espacios.
- Que las tres estadísticas (fuerza, inteligencia y carisma) sean números enteros, cada una entre 1 y 4, y que la suma total sea exactamente 7.

Si todo es válido, devuelve una ficha del personaje con sus estadísticas representadas en puntos llenos (●) y vacíos (○).

### Ejemplo

```
>>> create_character('ren', 4, 2, 1)
ren
STR ●●●●○○○○○○
INT ●●○○○○○○○○
CHA ●○○○○○○○○○
```

## Cómo ejecutarlo

```bash
python create_character.py
```

## Notas

Ejercicio resuelto de forma individual.
