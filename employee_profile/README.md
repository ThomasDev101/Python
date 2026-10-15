# Valificador de Perfiles de Empleado 🛡️📊

Script en Python desarrollado como práctica enfocada en **manipulación de cadenas de texto (strings), limpieza de datos y técnicas de validación**.

---

## 🚀 Resumen
Este script procesa datos sin procesar de empleados (correos electrónicos, nombres, números de teléfono, direcciones y códigos de empleado) para demostrar el dominio de los métodos integrados de cadenas en Python. Estandariza formatos, extrae subcadenas específicas y verifica la integridad de los datos.

---

## 🛠️ Conceptos y Métodos Clave Cubiertos

* **Búsqueda y Slices:** Localización de caracteres usando `.find()` y extracción de subcadenas mediante notación de corte (`[:at_position]`).
* **Sanitización de Datos:** Eliminación de espacios en blanco y estandarización de mayúsculas/minúsculas con `.strip()`, `.lower()` y `.upper()`.
* **Transformación de Texto:** Reemplazo de caracteres y formato de nombres de visualización usando `.replace()` y `.title()`.
* **Conversión a Listas:** División y reensamblaje de datos de texto estructurados con `.split()` y `'.'.join()`.
* **Validación y Auditoría:** Comprobación de prefijos y sufijos con `.startswith()` y `.endswith()`, además del conteo de ocurrencias usando `.count()`.

---

## 💻 Estructura del Código

```python
# 1. Análisis de correo y extracción de nombre de usuario
# 2. Limpieza de nombres y correos (espacios y mayúsculas/minúsculas)
# 3. Formato de número de teléfono
# 4. Análisis y reensamblaje de direcciones
# 5. Validación de prefijos en códigos y conteo de caracteres