# **Challenge AluraStore**

Este repositorio contiene un análisis comparativo del desempeño de cuatro tiendas:

- `Tienda_1`  
- `Tienda_2`  
- `Tienda_3`  
- `Tienda_4`  

---

## 📁 Contenido de los datos

Los datos utilizados se encuentran en cuatro archivos `.csv`, cada archivo contiene información sobre:

- Productos vendidos  
- Precios  
- Calificaciones de los clientes  
- Costos de envío

---

## 📊 Métricas evaluadas

Se analizaron las siguientes métricas para cada tienda:

- **Ventas Totales**: Suma total de precios de los productos vendidos.  
- **Calificación Promedio**: Nivel de satisfacción general de los clientes.  
- **% de Calificaciones Malas**: Porcentaje de reviews de 1 y 2 estrellas.  
- **Costo de Envío Promedio**: Costo logístico promedio por pedido.

---

## ⚙️ Metodología

El análisis siguió los siguientes pasos:

1. **Carga y limpieza de datos** desde archivos `.csv` (utilizando `pandas`).  
2. **Cálculo de métricas clave** para cada tienda:
   - Total de ventas
   - Calificación promedio
   - Distribución de calificaciones (identificación de calificaciones malas)
   - Costo de envío promedio  
3. **Visualización** de los resultados mediante gráficos (matplotlib/seaborn).
4. **Comparación multicriterio** para determinar la tienda con peor desempeño global.

---

## 🚀 Ejecución

### Requisitos
- Python 3.0+
- Bibliotecas: `pandas`, `matplotlib`

### Pasos

1. Clona o descarga los archivos .csv de cada tienda.

## 📄 Informe Final

Se realizaron los siguientes análisis para determinar cual es la mejor tienda para invertir:
1. Escala de Negocio
2. Concentración de demanda (riesgo)
3. Atractivo por categoría
4. Eficiencia Operacional

Se concluye que la mejor opción para invertir al corto plazo es la **Tienda 1**.
