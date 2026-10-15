# 🍳 Inventario de cocina (Python)

Práctica del taller de Python de [freeCodeCamp](https://www.freecodecamp.org/): un pequeño programa que lleva el control del stock de una cocina y simula cocinar un huevo frito.

## 📋 Descripción

El programa gestiona tres ingredientes (huevos, harina y azúcar) y permite:

- Consultar el inventario total de la cocina.
- Usar huevos comprobando que haya suficientes.
- Preparar un huevo frito, descontando del stock los huevos utilizados.

## 🧠 Conceptos practicados

- Variables y tipos de datos
- Funciones con parámetros y valores de retorno (`return`)
- Condicionales (`if` / `else`)
- f-strings para dar formato a la salida
- Ámbito de variables (global vs. local)

## 🔧 Funciones

| Función | Descripción |
|---|---|
| `check_kitchen_stock()` | Muestra el total de ingredientes y la cantidad de cada uno. |
| `use_eggs(available_eggs, eggs_to_use)` | Resta huevos del stock. Si no hay suficientes, avisa y devuelve la cantidad original. |
| `make_fried_egg(available_eggs)` | Si hay al menos 1 huevo, lo usa y prepara un huevo frito. Devuelve los huevos restantes. |

## ▶️ Cómo ejecutarlo

Necesitas tener [Python 3](https://www.python.org/downloads/) instalado.

1. Clona el repositorio o descarga el archivo `inventario_cocina.py`.
2. Abre una terminal en la carpeta del archivo.
3. Ejecuta:

```bash
python inventario_cocina.py
```

> En Mac o Linux puede ser necesario usar `python3 inventario_cocina.py`.

## 🖥️ Salida esperada

```
The kitchen has 6 total items:
- 1 eggs
- 2 flour
- 3 sugar
1 egg(s) used out of 1 available.
1
1 egg(s) used out of 1 available.
Made a fried egg. Yummy!
The kitchen has 5 total items:
- 0 eggs
- 2 flour
- 3 sugar
```

## 💡 Nota de aprendizaje

La primera llamada a `use_eggs(available_eggs, 1)` no modifica el inventario, porque el valor devuelto no se guarda en ninguna variable (por eso el `print` posterior sigue mostrando `1`). En cambio, en `available_eggs = make_fried_egg(available_eggs)` sí se reasigna el resultado y el stock se actualiza a `0`.

## 📚 Fuente

Actividad del currículo de Python de [freeCodeCamp](https://www.freecodecamp.org/).