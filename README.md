# Inventario

Este proyecto es un sistema básico de inventario para poder gestionar productos de una tienda. 

## Funcionalidades

El proyecto incluye las siguientes funciones:

- **Agregar producto**: Permite añadir un nuevo producto al inventario o actualizar la cantidad si ya existe.
- **Ver inventario**: Muestra todos los productos con su nombre, precio y cantidad.
- **Buscar producto**: Permite buscar un producto por su nombre y ver sus detalles.
- **Actualizar stock**: Permite modificar la cantidad de un producto existente.
- **Eliminar producto**: Permite eliminar un producto del inventario.
- **Calcular valor del inventario**: Suma el valor total de todos los productos (`precio x cantidad`).

## Estructura de datos

- **Inventario**: Lista de diccionarios, donde cada diccionario representa un producto con las claves:
  - `nombre` → Nombre del producto
  - `precio` → Precio unitario del producto
  - `cantidad` → Cantidad disponible en stock

Ejemplo:

```python
inventario = [
    {"nombre": "Camisa", "precio": 20, "cantidad": 50},
    {"nombre": "Pantalón", "precio": 30, "cantidad": 30}
]
