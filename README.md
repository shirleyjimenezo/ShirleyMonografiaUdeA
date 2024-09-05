## Resumen del Proyecto

La rotación de empleados es un problema creciente para las empresas, implicando costos elevados en reclutamiento y capacitación. En una empresa de seguros, la contratación de nuevos vendedores conlleva un periodo de ajuste en habilidades de ventas, debido a la experiencia necesaria. Identificar posibles bajas futuras permite al área de Gestión Humana implementar intervenciones para mejorar la retención.

Este proyecto presenta varios experimentos para predecir la deserción de empleados, con la variable de salida siendo 1 para deserción y 0 para permanencia. Se probaron tres modelos de Machine Learning:

1. **Árbol de Decisión:** Se realizaron dos iteraciones, una con parámetros elegidos manualmente y otra con funciones para optimizar los parámetros.
2. **Máquina de Vectores de Soporte (SVM):** Aplicando funciones para encontrar los mejores parámetros.
3. **Regresión Logística:** También utilizando funciones para los mejores parámetros.

Finalmente, se ejecutó una iteración adicional con los tres modelos bajo validación cruzada. Los resultados mostraron que el modelo de Árbol de Decisión, utilizando validación cruzada y parámetros optimizados, es el más efectivo para predecir las bajas de empleados. Esto permitirá a la empresa identificar a los empleados en riesgo y tomar medidas de retención a tiempo.
