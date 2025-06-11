# 🛒 Análisis de Ventas: Alura Store LATAM

Este notebook analiza los datos de ventas de **4 tiendas** para tomar una decisión informada sobre **cuál tienda vender o reestructurar**.

---

## 📁 Archivos utilizados

Se cargan los datos desde los siguientes enlaces públicos (GitHub):

- tienda_1.csv
- tienda_2.csv
- tienda_3.csv
- tienda_4.csv

---

## 🔎 Estructura del análisis

El análisis está dividido en 5 secciones principales:

### 1. Facturación Total por Tienda
Se suma el precio del producto y el costo de envío para obtener la facturación. Esto nos permite ver qué tienda genera más ingresos.

### 2. Ventas por Categoría
Se identifican las categorías más vendidas por tienda, analizando el tipo de productos que generan más movimiento.

### 3. Calificación Promedio
Se evalúa la satisfacción del cliente según las calificaciones (1 a 5) para cada tienda.

### 4. Productos Más y Menos Vendidos
Se listan los productos más populares y aquellos con menos salida, ayudando a tomar decisiones de inventario.

### 5. Costo de Envío Promedio
Se calcula el costo promedio de envío por tienda, importante para analizar la eficiencia logística.

---

## 🧠 Insight Final: ¿Qué tienda vender?

Se consolida toda la información y se identifican métricas clave como:

- Facturación total
- Calificación promedio
- Costo de envío
- Cantidad de productos vendidos

> La tienda **menos rentable y eficiente** se recomienda para **venta o reestructuración**.

---

## ✅ Conclusión

**Tienda 2** es la candidata ideal para ser vendida debido a:

- Baja facturación
- Mala calificación
- Altos costos logísticos
- Pocas ventas

---

## 📌 Requisitos

Este notebook utiliza `pandas` y `matplotlib`. Asegúrate de tenerlos instalados con:

```bash
pip install pandas matplotlib
