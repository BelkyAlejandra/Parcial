# Parcial
Este repositorio muestra los códigos del primer parcial de Física Computacional II. 

1. **¿De dónde se sacó la base de datos?** La base de datos fue extraída de la página Kaggle: https://www.kaggle.com/datasets/uciml/biomechanical-features-of-orthopedic-patients
3. **¿Qué se hizo?** Lo que se hizo fue aplicar cuatro métodos de aprendizaje no supervisado, a saberse: MeanShift, DBSCAN, Kmeans y Hierarchical Clustering. 
4. **¿Cómo se hizo?** se unieron las clases Hernias y Normal, de manera que de antemano se esperaba que hubiesen dos clusters. Por lo tanto, se tomó un gráfico de referencia, con el cuál se comparaban los cluster que arrojaban los métodos.
5. **¿Qué se obtuvo?** que el método que mejor clasificó fue Hierarchical Clustering, con un accuracy de aproximadamente 98%
