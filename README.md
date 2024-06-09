# TFM---Estefania-Aracena-Lenin-Medina
Repositorio con códigos implementados para Trabajo Fin de Máster (TFM) de Máster Universitario en Análisis y Visualización de Datos Masivos de Universidad Internacional de La Rioja

# TFM - Sistema de alerta ante la presencia de Didymosphenia Geminata en agua dulce con técnicas de inteligencia artificial

Presentado por: Aracena Vallejos, Estefania – Medina Jiménez, Lenin  
Directora: Prados Privado, María

- EDA TFM.ipynb: contiene el análisis exploratorio de datos y limpieza del set de datos
- Clustering-data.ipynb y Clustering-pca.ipynb: contiene la implementación de la técnica de clustering para el set de datos
- Random Forest TFM.ipynb: contiene un modelo pre-entrenado de Random Forest para el set de datos
- Neural Network TFM.ipynb: contiene un modelo pre-entrenado de redes neuronales para el set de datos
- Grafo -1 TFM.ipynb y Grafo -2 TFM.ipynb: contiene un modelo pre entrenado de redes neuronales convolucionales para grafos para el set de datos

# Abstract
This master’s thesis follows the detection and control issue of Didymosphenia geminata (Didymo), an invasive algae species that has been spread in many countries, including Chile, and it has caused serious damage to aquatic ecosystems and a negative impact in activities related to water. The aim is to develop an alert system based on artificial intelligence techniques that allows to identify the presence of Didymo within different hydrographic subbasins and rate the algae coverage. To complete the task, a data set provided by the Instituto Fomento Pesquero from Puerto Montt has been handled, it includes information about physical and chemical parameters of the water as well as the presence or absence of Didymo and the algae coverage percentage in each sample. Different methods of data analysis have been applied, such as clustering, ensemble learning (random forest, neural networks) and graph convolutional networks, to develop classification and prediction models that are compare with each other in terms of accuracy and robustness. The results showed that graph convolutional networks are the most suitable method for this problem, they are capable to capture the relationships between the parameters and the characteristics of each sampling site with the coverage percentage of Didymo at the subbasins of the chilean southern rivers.
Keywords: Didymosphenia geminata, Didymo, artificial intelligence, clustering, ensembled learning, graph, convolutional networks
