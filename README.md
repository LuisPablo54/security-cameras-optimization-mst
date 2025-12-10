# Proyecto: Optimización de la Distribución de Cámaras de Seguridad mediante Clustering y MST en el Centro de León, Guanajuato

Este proyecto implementa un sistema para:
1. Cargar un grafo urbano a partir de datos de nodos y calles.
2. Agrupar los nodos utilizando k-means mediante las coordenadas geográficas.
3. Generar un subgrafo por cluster utilizando únicamente las calles reales del mapa.
4. Calcular el Árbol de Expansión Mínima (MST) del subgrafo de cada cluster utilizando el algoritmo de Prim.
5. Visualizar:
   - El grafo completo.
   - Los clusters.
   - El MST de cada cluster sobre el mapa original.

El proyecto se implementa en Python y utiliza NetworkX, Pandas, NumPy y Matplotlib.


