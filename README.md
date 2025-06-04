# Data-Science-Alura
Primer desafío de Data Science en Alura Latam
# 📊 Análisis de Tiendas - Alura Store

Este proyecto tiene como objetivo ayudar al Sr. Juan a decidir qué tienda de su cadena **Alura Store** debería vender para iniciar un nuevo emprendimiento. El análisis se basa en datos históricos de ventas, rendimiento por categorías, productos más y menos vendidos, calificaciones de usuarios y costos promedio de envío.

---
## 📄 Visualización del Informe

El archivo [`index.html`](https://AlejoCald.github.io/Data-Science-Alura/index.html) contiene una versión del informe generado con **Jupyter Notebook**, exportado como HTML. Fue subido a GitHub Pages para facilitar su visualización online.

### 🔗 Accede al informe visual

👉 Puedes ver la versión aquí:  
https://alejocald.github.io/Data-Science-Alura/
---
## 🧠 Tecnologías y herramientas utilizadas

- **Python 3.10+**
- **Jutpiter Notebook / Google Colab**
- **Bibliotecas de visualización**:
  - `matplotlib`
  - `numpy`
- **Tipado y documentación**:
  - `typing`
 **Github Pages**

---

## 📁 Estructura del proyecto

El análisis contiene los siguientes apartados:

1. **Carga y preprocesamiento de datos**
2. **Cálculo de ingresos por tienda**
3. **Análisis de productos más y menos vendidos**
4. **Análisis de categorías y cantidad de ventas**
5. **Evaluación de calificaciones**
6. **Costo de envío promedio**
7. **Visualizaciones gráficas**
8. **Recomendación final basada en datos**

---

## 🧮 Funciones destacadas

- `agrupa_columna_tabla()`: Agrupa columnas de datos.
- `suma_venta_producto_categoria()`: Suma las ventas por categoría.
- `promedio()`: Calcula el promedio de una lista.
- `obtiene_ejes()`: Prepara los ejes X e Y para las gráficas.
- `muestraVenta()`: Muestra productos más/menos vendidos.
- Funciones tipadas usando `typing`: List, Tuple, Union, Dict, etc.

---

## 📈 Visualizaciones

Se utilizaron gráficos de barras, de linea y dispersión para comparar visualmente:

- Facturación por tienda
- Productos más y menos vendidos
- Calificación de las tiendas
- Costo promedio de envío

---

## 🧪 Requisitos

Asegúrate de tener las siguientes bibliotecas instaladas si no estás usando Google Colab:

```bash
pip install matplotlib numpy
