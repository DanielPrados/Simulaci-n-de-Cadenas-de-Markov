# Simulacion-de-Cadenas-de-Markov
Este repositorio contiene un cuaderno de Jupyter centrado en el aprendizaje y la implementación de simulaciones de trayectorias de Cadenas de Markov (MC) utilizando herramientas estándar de Machine Learning en Python.


1.  Objetivos:
  - Simular trayectorias de una Cadena de Markov a partir de una matriz de transición y una distribución inicial.
  
  - Optimizar el rendimiento del código mediante la vectorización con Numpy, eliminando bucles innecesarios.
  
  - Visualizar resultados mediante gráficos de trayectorias (sample paths).
  
  -Explorar conceptos teóricos como el teorema de convergencia y el teorema ergódico.
  
  2. Tecnologías Utilizadas
   - Python
  
   - Numpy: Para el cálculo numérico y manejo de matrices.
  
   - Matplotlib: Para la generación de visualizaciones y gráficos de pasos (plt.step).
  
3.  Contenido del Notebook

  - Simulación de Trayectorias
  Se presentan dos enfoques para simular las trayectorias:
  
  Versión Básica: Implementada con bucles for anidados.
  
  Versión Eficiente: Optimizada para procesar múltiples muestras simultáneamente usando operaciones vectorizadas de Numpy, lo que reduce drásticamente el tiempo de ejecución .
  
  -  Visualización
    El notebook incluye código para generar gráficos que muestran el comportamiento de varios caminantes a lo largo del tiempo, facilitando la comprensión visual      de cómo evolucionan los estados en la cadena.

