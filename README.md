El presente repositorio contiene una serie de notebooks (jupyter notebook) con codigos de consolidaciones de varios materiales que permitan aprender y aplicar tanto librerias, tecnicas, metodos y modelos de Machine & Deep Learning. Este repositorio NO posee un fin lucrativo. Su propósito es el aprendizaje abierto con el fin de poder ayudar y fomentar el desarrollo de aplicaciones-soluciones basadas en datos mediante los ejemplos dentro de los códigos expuestos.

**Importante**: El numero del notebook indica si es reciente o no, por ejemplo si tenemos los notebooks **"4. DeepL Learning"** y **"7. Catboost regression"**, el notebook con número **7** es el más reciente agregado al repositorio. 

Los códigos realizados tienen como base consulta a la documentación de la libreria, incluyendo su uso y ejemplos, así como algún libro, foros o blogs vinculados a la aplicación del mismo. En los notebooks cuando se utilizan datos específicos se dejará alguna forma de poder ubicar los datos desde su origen, es decir, mediante el link al repositorio fuente, la pagina web, el nombre del dataset u similar.

**Video:** Una pequeña muestra de resultados de DeepQ (Reinforcement Learning)
[[Link video youtube]](https://youtube.com/shorts/mnR2g9tkh4k)


Principales fuentes consultadas o de material extraido como imagenes u otra forma:
  1) Aurélien Géron (O'Reilly) : Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow
  2) Andreas C. Müller and Sarah Guido (O'Reilly): Introduction to Machine Learning with Python A Guide for Data Scientists
  3) tensorflow.org
  4) scikit-learn.org
  5) tslearn.readthedocs
  6) scipy
  7) pycaret
  8) h2o
  9) pytorch
  10) skforecast & statsmodel (**En forecasting (series de tiempo) se recomienda este - ver notebook**)
  11) statsforecast
  12) pyAF
  13) surprise (**En sistemas de recomendación se recomienda este - ver notebook**)
  14) tensorflow-recommenders
  15) Keras-RL (Reinforcement Learning)
  16) Gym (Reinforcement Learning)
  17) modelo YOLO - Computer Vision (Segun modelo pre-entrenados de Ultralytics)
  18) otras librerias/repositorios/blogs/foros vinculados a los enlaces previos
  19) Dataset usados de páginas como Kaggle

**Nota**: En algunos casos puede que se deba modificar el código debido a cambios en la libreria en versiones nuevas, generandose alguna incompatibilidad
que genere algún error en caso de ejecutarse.

**Cuidado**: Casos observados de potencial error en versiones nuevas de librerias
1) El retorno de alguna funcion de scikit no devuelve formato numpy sino dataframe o viceversa generando inconsistencia al colocarse X[indice] (numpy) vs X.iloc[indice] ó X.loc[indice] (pandas), por lo que deberá tenerse cuidado de manipular los elementos segun matriz (numpy) o dataframe (pandas).
