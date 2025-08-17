# **Challenge AluraStore**

Este repositorio contiene un análisis comparativo del desempeño de cuatro tiendas:

- `Tienda_1`  
- `Tienda_2`  
- `Tienda_3`  
- `Tienda_4`  

El objetivo principal es identificar, mediante un enfoque multicriterio, **cuál tienda debería cerrarse** en función de su bajo desempeño general.

---

## 📁 Contenido de los datos

Los datos utilizados se encuentran en cuatro archivos `.csv`, descritos en el notebook de trabajo:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene información sobre:

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
- Python 3.8+
- Bibliotecas: `pandas`, `matplotlib`, `seaborn` (opcional: `jupyter`)

### Pasos

1. Clona o descarga este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/Challenge-AluraStore.git
