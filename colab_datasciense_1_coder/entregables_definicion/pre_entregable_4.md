# Checkpoint: EDA visual del dataset del proyecto

Un buen Análisis Exploratorio de Datos (EDA) visual no busca hacer "gráficos bonitos", sino encontrar patrones, detectar anomalías y validar hipótesis que guiarán el resto de tu proyecto de Ciencia de Datos.


## ¿Qué sigue? 

Este checkpoint de visualización es el ***puente hacia el análisis predictivo***. Las relaciones que descubras hoy decidirán qué variables usarás en tus modelos de Machine Learning más adelante.

## Objetivo de aprendizaje

Consolidar un EDA visual preliminar utilizando Matplotlib y Seaborn, aplicando principios de jerarquía visual y storytelling para comunicar hallazgos relevantes del dataset de tu proyecto.

## Qué construir
Debes producir un ***informe visual que resuma*** los hallazgos más importantes de tu dataset. No se trata de exportar todos los gráficos posibles, sino de seleccionar aquellos que realmente aporten valor al entendimiento del problema de negocio.

## El artefacto debe incluir:

- Análisis Univariado: Al menos ***2 gráficos*** que muestren la distribución de las variables más importantes (ej. histogramas con KDE).

- Análisis Bivariado/Multivariado: Al menos ***3 gráficos*** que muestren relaciones o comparaciones (ej. Boxplots para comparar categorías, Scatter plots para ver correlaciones o un Heatmap de correlación general).

- Interpretación: Cada gráfico debe estar acompañado de una breve descripción (2-3 líneas) que explique qué estamos viendo y qué ***conclusión preliminar*** podemos sacar.

### Errores comunes a evitar

- El "vómito de gráficos": Incluir 20 gráficos sin explicación. Es mejor 5 gráficos bien analizados que 20 sin sentido.

- Ejes sin escala o etiqueta: Un gráfico sin ylabel es solo una forma abstracta; el lector no sabe si hablamos de pesos, dólares o kilogramos.
- Ignorar la distribución: Hacer análisis de correlación sin haber visto primero si los datos tienen outliers (valores atípicos) que puedan estar sesgando la relación.

## Conexión con el entregable final

***Este EDA visual será el núcleo de tu presentación final***. En los módulos siguientes, cuando apliques modelos de Machine Learning, volverás a estos gráficos para explicar por qué el modelo se comporta de cierta manera. Lo que visualices hoy es el mapa de tu proyecto.


### Instrucciones del Ejercicio: EDA Visual del Proyecto

El objetivo es transformar esos datos en conocimiento visual.

Requisitos del archivo:
Contenido:

- Portada: Título del proyecto y nombre del estudiante.

- Resumen del Dataset: Breve descripción de qué datos estás analizando (1 párrafo).

- Visualizaciones (Mínimo 5):
    - Al menos 1 Histograma o KDE (Distribución).
    - Al menos 1 Boxplot o Violinplot (Comparación por categorías).
    - Al menos 1 Scatter Plot o Heatmap de correlación (Relación entre variables).

- Análisis por gráfico: 
    - Debajo de cada imagen, escribe un breve párrafo explicando qué descubriste (ej: "Se observa que la variable X tiene un sesgo a la derecha y presenta outliers por encima de los 5000 unidades").

- Pasos técnicos recomendados:
    - Carga tu dataset limpio en un Jupyter Notebook.
    - Genera los gráficos usando seaborn y personalízalos con matplotlib.
    - Asegúrate de que todos los gráficos usen el mismo estilo visual (ej. sns.set_theme()).
    