# H2_DM

En esta tarea, aplicamos clustering con K-Means al dataset Iris y comparamos los resultados con las etiquetas reales de las especies. Primero, exploramos los datos mediante gráficos de dispersión e histogramas para analizar sus distribuciones y relaciones. Luego, utilizamos K-Means con diferentes valores de k para agrupar los datos basándonos en las características de los sépalos y pétalos, observando cómo la forma de cada parte influye en la segmentación.

Para determinar el número óptimo de clusters, aplicamos el método del codo, el cual indicó que k=3 era la mejor opción, lo que coincide con las tres especies presentes en el dataset. También probamos escalado de datos para evaluar su impacto en los resultados de K-Means.

Al comparar los clusters generados con las etiquetas reales, notamos que Setosa se separa claramente cuando se usan sépalos, pero Versicolor y Virginica se solapan, lo que demuestra que los pétalos ofrecen una mejor segmentación. En conclusión, aunque K-Means es útil para este problema, su efectividad depende de las variables utilizadas, y combinar sépalos y pétalos mejora significativamente la clasificación.
