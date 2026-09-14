# Taller Data Sets - Grupo 2

Repositorio con datasets de ejemplo para practicar limpieza, analisis y visualizacion de datos, usando como contexto el negocio real de materiales de construccion PVCENTRO (tiendas San Gil y Socorro, Santander).

## Archivos

- `ventas_pvcentro.csv`: 60 registros de ventas (fecha, tienda, categoria, producto, cantidad, precio_unitario, total). Util para practicar agregaciones, series de tiempo y comparaciones entre tiendas.
- `inventario_pvcentro.csv`: inventario por producto y tienda (stock, costo_unitario). Incluye a proposito algunos datos "sucios" (valores vacios, texto en minuscula inconsistente, un valor negativo invalido, espacios extra) para practicar limpieza de datos.

## Ejercicios sugeridos

1. Cargar ambos CSV con pandas y revisar tipos de datos y valores nulos.
2. Limpiar inventario_pvcentro.csv: normalizar nombres de tienda, corregir o eliminar el stock negativo, decidir que hacer con el valor vacio, quitar espacios extra en nombres de producto.
3. Calcular ventas totales por tienda y por categoria.
4. Identificar el producto mas vendido (por cantidad y por valor).
5. Cruzar ventas e inventario: para cada producto, calcular cuantos dias de inventario quedan al ritmo de venta actual.
6. Graficar ventas por dia y por categoria.

Datos sinteticos generados con fines academicos (no son datos reales de clientes).
