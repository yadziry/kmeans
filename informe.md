# **Actividad de aprendizaje AA2 - Informe de agrupamiento: datos en Markdown aplicando K-means en Python.**  

## **1. Introducción**  
Se utilizó el algoritmo **K-Means** para segmentar clientes de un centro comercial basado en:  
- **Ingreso Anual (k$)**  
- **Puntuación de Gasto (1-100)**  

## **2. Método del Codo (Selección de K óptimo)**  
![Gráfico del Codo](https://github.com/yadziry/kmeans/raw/main/codo.png)  
**K=5** fue elegido por ser el punto de inflexión.  

## **3. Resultados de Clustering**  
![Clusters Finales](https://github.com/yadziry/kmeans/raw/main/clusters.png)  

**Perfiles encontrados:**  
| Cluster | Comportamiento |  
|---------|----------------|  
| 0 | Alto ingreso, bajo gasto |  
| 1 | Medio ingreso, alto gasto (target ideal) |  

## **4. Conclusiones**  
- K=5 permite una segmentación clara.  
- El **Cluster 1** es el mejor target para promociones.  

**Autor:** Melany Chicaiza  
