# Análisis de desempeño financiero de tiendas

📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el desempeño financiero y comercial de cuatro tiendas pertenecientes a una misma empresa, con el fin de identificar cuál de ellas presenta menor impacto estratégico y podría ser considerada para venta o reestructuración.

🎯 Objetivos del Análisis

- Calcular el ingreso total por tienda.
- Analizar la distribución de ventas por categoría.
- Evaluar la calificación promedio de los clientes.
- Identificar los productos más y menos vendidos por tienda.
- Calcular el costo de envío promedio.
- Proponer una recomendación estratégica basada en los resultados.

🛠️ Tecnologías usadas
- Python 3 como lenguaje de programación
- Jupyter Notebook como entorno de desarrollo
- Pandas para manipulación y análisis de datos
- NumPy para cálculos numéricos
- Matplotlib para visualización de datos

📂 Estrucutura del proyecto
Proyecto
├── datos
│   ├── tienda1.csv
│   ├── tienda2.csv
│   ├── tienda3.csv
│   └── tienda4.csv
├── AluraStoreLatam.ipynb
└── README.md

🔎 Metodología

1. Carga y limpieza de datos
    - Verificación de valores nulos.
    - Revisión de tipos de datos.
    - Concatenación de los DataFrames en uno solo para facilitar el análisis comparativo.
2. Análisis exploratorio
    - Ingreso total por tienda.
    - Ventas por categoría.
    - Productos más y menos vendidos (Top 3 y Bottom 3 por tienda).
    - Valoración promedio.
    - Costo de envío promedio.
3. Visualización
    - Gráficos de barras para comparación de ingresos.
    - Barras agrupadas para categorías y productos.
    - Visualización comparativa de indicadores clave.

📊 Principales Hallazgos

- La Tienda 1 presenta el mayor ingreso total.
- La Tienda 4 registra el menor ingreso comparativo.
- Existen diferencias en los productos más vendidos entre tiendas, lo que indica dinámicas comerciales independientes.
- Algunas categorías concentran mayor volumen de ventas, especialmente muebles, electrónicos y juguetes.
- La valoración promedio es similar entre tiendas, con ligeras variaciones.

🏁 Conclusión

Tras evaluar los indicadores financieros y comerciales, se determinó que la Tienda 4 representa el menor impacto en la rentabilidad global del negocio.

En caso de que el Sr. Juan decida vender una tienda, la Tienda 4 sería la opción estratégicamente más viable. Alternativamente, se recomienda una reestructuración enfocada en las categorías con mayor rotación para optimizar su desempeño.

▶ Cómo Ejecutar el Proyecto

-  Clonar el repositorio:

git clone https://github.com/Carolina1Cortes/Analisis-de-desempeno-financiero-de-tiendas.git

- Instalar dependencias:

pip install pandas matplotlib

- Ejecutar el notebook:
Abrir el archivo analisis_tiendas.ipynb en Jupyter Notebook o Google Colab.

📌 Posibles Mejoras Futuras

- Incorporar análisis geográfico de ventas.
- Implementar visualizaciones interactivas (Plotly o Folium).
- Aplicar modelos predictivos de ventas.
- Análisis de rentabilidad por categoría.

👩‍💻 Autora

Carolina Cortes
Proyecto desarrollado como parte de formación en Data Science.
