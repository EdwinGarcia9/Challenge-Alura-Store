# Análisis Comparativo de Tiendas

## Descripción

Este proyecto realiza un análisis comparativo de 4 tiendas utilizando datos de ventas, productos y logística. El análisis se centra en identificar patrones de rendimiento, productos más vendidos, calificaciones y eficiencia operativa de cada ubicación.

## Fuente de Datos

Los datos provienen del repositorio de Alura Challenge Data Science LATAM:
- Tienda 1: `tienda_1.csv`
- Tienda 2: `tienda_2.csv`
- Tienda 3: `tienda_3.csv`
- Tienda 4: `tienda_4.csv`

## Requisitos

```bash
pip install pandas
```

## Dependencias

- Python 3.x
- pandas

## Análisis Realizados

### 1. **Ingresos por Tienda**
Cálculo de los ingresos totales generados por cada tienda mediante la suma de todos los precios de venta.

### 2. **Análisis de Categorías**
Agrupación y conteo de productos vendidos por categoría en cada tienda, ordenados de mayor a menor cantidad.

### 3. **Calificaciones Promedio**
Cálculo de la calificación promedio por categoría de producto en cada tienda.

### 4. **Top de Productos**
Identificación de los productos más vendidos en cada tienda mediante conteo y ordenamiento descendente.

### 5. **Costos de Envío**
Análisis del costo promedio de envío por tienda.

## Uso

1. Ejecutar el notebook completo para cargar los datos desde las URLs proporcionadas
2. Los análisis se ejecutan secuencialmente mostrando resultados por tienda
3. Las conclusiones se presentan al final del análisis

## Principales Hallazgos

### Rendimiento por Ingresos
- **Tienda 1**: Mayor generadora de ingresos
- **Tienda 4**: Menor rendimiento en ingresos

### Oferta de Productos
- No se observan diferencias significativas en categorías y productos más vendidos entre tiendas
- El desempeño está más relacionado con factores de ubicación que con la oferta

### Costos Logísticos
- **Tienda 1**: Mayor costo de envío, pero ingresos superiores que compensan el gasto
- **Tienda 4**: Menor costo de envío, pero ingresos significativamente más bajos

## Conclusión

**Desde una perspectiva de costo-beneficio, la Tienda 1 resulta claramente más eficiente y rentable que la Tienda 4.**

A pesar de tener mayores costos logísticos, la Tienda 1 genera suficientes ingresos para justificar la inversión, mientras que la Tienda 4, aunque opera con menores costos, no logra generar ingresos suficientes para ser competitiva.

## Estructura del Código

```
├── Carga de datos (4 tiendas)
├── Análisis de ingresos
├── Análisis de categorías
├── Análisis de calificaciones
├── Top de productos
├── Análisis de costos de envío
└── Conclusiones
```
