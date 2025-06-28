# 📊 Resumen de Fundamentos del Proyecto de Análisis de Datos

## 1. 🎯 Objetivo del proyecto

Analizar las ventas realizadas en tres sucursales de supermercado en Myanmar durante el primer trimestre de 2019, con el fin de identificar los productos más vendidos, los patrones de compra por tipo de cliente y los métodos de pago más utilizados.


## 2. 🗂️ Descripción del conjunto de datos

- **Total de registros:** 1.000 transacciones
- **Año:** 2019
- **Columnas principales:** 
  - Sucursal (`Branch`)
  - Ciudad (`City`)
  - Género del cliente (`Gender`)
  - Producto (`Product line`)
  - Cantidad (`Quantity`)
  - Total (`Total`)
  - Fecha (`Date`)
  - Hora (`Time`)
  - Método de pago (`Payment`)
- **Fuente:** https://gist.github.com/sdukshis/7c2bb5e650ac567eefb7c939c4c4c8ff#file-sales-csv

## 3. 🧹 Limpieza y preparación de los datos

- Se detectaron fechas mal formateadas y fueron convertidas al formato `DD/MM/AAAA`
- Se aplicaron fórmulas para validar tipos de datos y corregir errores en fechas
- Se creó una columna adicional para extraer el **día de la semana**
- Se estandarizó el formato numérico en las columnas de ventas y cantidades
- Se validó que todos los valores fueran consistentes para permitir el proceso análisis

## 4. 📈 Métricas analizadas

1. **Ventas totales por sucursal**
2. **Producto más vendido por sucursal**
3. **Producto menos vendido por sucursal**
4. **Total de ventas por género**
5. **Producto más comprado por género**
6. **Distribución de métodos de pago por sucursal**
7. **Ticket promedio por sucursal**
8. **Ticket promedio general**
9. **Cantidad de transacciones por día de la semana**
10. **Ventas totales por día**

## 5. 🧮 Herramientas y funciones utilizadas

- **Fórmulas de Excel:**
  - `SUM()`
  - `COUNT()`
  - `TEXT()`
  - `DATE()`
- **Tablas dinámicas** para el resumen de métricas
- **Segmentación por filtros** (Sucursal, Producto, Género, Fecha)
- **Gráficos** de columnas, barras y líneas para representar resultados visualmente