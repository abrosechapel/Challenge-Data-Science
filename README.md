
# Análisis de Datos – Challenge Data Science 📊
Autor: Carla Bailón

🧠 **Propósito del análisis**

El propósito de este informe es apoyar al Sr. Juan, propietario de la cadena Alura Store, en la decisión de vender una de sus cuatro tiendas. La venta se enmarca en su interés por iniciar un nuevo emprendimiento, por lo que se requiere una decisión informada basada en un análisis detallado de los datos de ventas, calificaciones de clientes, costos operativos y rendimiento general.

Se han analizado múltiples factores de cada tienda: volumen de ventas, ingreso neto, opiniones de clientes, costo de envío, categorías y productos vendidos así como también se han utilizado algunos gráficos. El objetivo es identificar cuál tienda presenta un rendimiento más bajo así justificar su posible venta.

📁 **Estructura del proyecto**

```bash
├── notebooks/ # Jupyter Notebooks con el análisis
│ └── Data_Science_Challenge_Alura.ipynb
├── README.md # Este archivo
```

**Estructura del proyecto:**

1. Análisis de datos
2. Visualización
3. Informe
4. Visualización geográfica

📈 **Ejemplos de gráficos e insights obtenidos**

A continuación se muestran algunos ejemplos de los resultados visuales generados durante el análisis:

### Ventas totales
Las ventas totales de todas las tiendas suman: 4403619200.

| Tienda   | Ventas Totales (S/.) |
|----------|----------------------|
| Tienda 1 | 1,150,880,400        |
| Tienda 2 | 1,116,343,500        |
| Tienda 3 | 1,098,019,600        |
| Tienda 4 | 1,038,375,700        |

Gráfico 1: Ventas totales
![Ventas Totales](https://github.com/abrosechapel/Challenge-Data-Science/blob/main/Images/VentasTotales.png)

Porcentaje de la venta total que representa cada tienda:

| Tienda   | % Ventas en relación al total |
|----------|-------------------------------|
| Tienda 1 | 26.13%                 |
| Tienda 2 | 25.35%                 |
| Tienda 3 | 24.93%                 |
| Tienda 4 | 23.58%                 |

En el siguiente gráfico de líneas se puede observar el comportamiento temporal de las ventas de las cuatro tiendas:


![Ventas Por Mes](https://github.com/abrosechapel/Challenge-Data-Science/blob/main/Images/VentasPorMes.png))


⚙️ **Instrucciones para ejecutar el notebook**

-Desarga la carpeta images para las imagenes y configura que se puedan ver en el Colab o en Jupyter. En el apartado de informe ya que tienen un ID las imágenes.

-Clona este repositorio:

bash
Copiar
Editar
git clone https://github.com/abrosechapel/Challenge-Data-Science.git
cd nChallenge-Data-Science
```bash
Copiar
Editar
git clone https://github.com/abrosechapel/Challenge-Data-Science.git
cd Challenge-Data-Science
```

-Abre el notebook:

bash
Copiar
Editar
jupyter notebook notebooks/main_analysis.ipynb

⚠️ Asegúrate de tener instalado Jupyter Notebook. Si no lo tienes, instálalo con: pip install notebook

