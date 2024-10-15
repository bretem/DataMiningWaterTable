## Predicción de la funcionalidad de las bombas de agua en Tanzania

Este repositorio contiene el código y la documentación del proyecto "Predicción de la funcionalidad de las bombas de agua en Tanzania mediante técnicas de aprendizaje automático". El proyecto tiene como objetivo abordar el problema crítico de las bombas de agua no funcionales en Tanzania mediante el desarrollo de modelos de aprendizaje automático para predecir el estado operativo de estas bombas.Este Proyecto se llevó a cabo entre febrero y abril de 2024.
## Descripción general del proyecto:
El acceso al agua potable es un problema importante en Tanzania, ya que muchas bombas de agua no funcionan o necesitan reparaciones. Este proyecto utiliza un conjunto de datos exhaustivo que contiene varias características relacionadas con las bombas de agua, incluida información geográfica, características de las bombas y detalles de gestión. El objetivo principal es desarrollar modelos predictivos utilizando múltiples técnicas de aprendizaje automático y comparar su rendimiento.
## Contenidos del repositorio:

"WaterTable_final.ipynb" : Jupyter Notebook que contiene el código para el análisis de datos, el preprocesamiento y el desarrollo de modelos.
## Modelos utilizados:

DecisionTreeClassifier

RandomForestClassifier

BaggingClassifier

AdaBoostClassifier

VotingClassifier

XGBClassifier

SVC
## Resultados:
El rendimiento de cada modelo se evaluó mediante precisión, recuperación, puntuación F1 y exactitud. Los algoritmos (VotingClassifier, RandomForestClassifier, XGB y Bagging ) mostraron el mejor rendimiento, logrando una precisión del 82%. Los resultados estan detallados  en el informe del proyecto ("report.htlm").
## Datos:
El conjunto de datos utilizado en este proyecto es proporcionado por el Ministerio de Agua de Tanzania en colaboración con Taarifa. Incluye información sobre 59.400 bombas de agua con 41 características. El conjunto de datos no está incluido en este repositorio y debe descargarse de la página del concurso DrivenData: https://www.drivendata.org/competitions/7/pump-it-/

## Grado:
Este proyecto recibió una puntuación de 82.07%

## Agradecimientos:
Este proyecto se completó como parte del módulo de Machine Learning, del Máster Data Science, Big Data & Business Analytics de la Universidad Complutense de Madrid. Un agradecimiento especial a los profesores y compañeros por su apoyo y orientación.

## Licencia:
Este proyecto está licenciado bajo la licencia MIT - ver archivo LICENSE para más detalles.
