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

1. Grafo generado del centro de la ciudad de León:
<img width="50%" alt="img1" src="https://github.com/user-attachments/assets/e533aa01-1efe-4d43-bd0b-9255f77572b5" />

2. Ubicación óptima para las cámaras de acuerdo con los parámetros establecidos
<img width="50%" alt="img2" src="https://github.com/user-attachments/assets/009dcf9a-6992-43a4-ac0f-344acb2690ca" />


3. Clusterización óptima para las cámaras
<img width="50%" alt="img3" src="https://github.com/user-attachments/assets/535b1f23-6dfd-4249-9076-888fc9d32b5f" />


4. Ruta ideal para la conexión de las cámaras utilizando algoritmo de Prim y A* para acoplarlo con la infraestructura urbana
<img width="50%" alt="img4" src="https://github.com/user-attachments/assets/25b68550-6fda-4434-9902-ece820e79e46" />

