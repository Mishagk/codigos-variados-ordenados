This repository contains a series of notebooks (jupyter notebook) with consolidated code from various materials that allow you to learn and apply libraries, techniques, methods, and models of Machine & Deep Learning. This repository does NOT have a profit-making purpose. Its purpose is open learning in order to help and promote the development of data-based applications and solutions through the examples within the exposed code.

**Relevant**: The notebook number indicates whether it is recent or not, for example if we have the notebooks "4. Deep Learning" and "7. Catboost regression", the notebook with number 7 is the most recent addition to the repository.

The codes are based on consultation of the library documentation, including its usage and examples, as well as books, forums, or blogs related to its application. In the notebooks, when specific data is used, there will be some way to locate the data from its source, that is, through a link to the source repository, the website, or even with the dataset name that could be searched on the internet or similar.

Main sources consulted or from which material such as Python libraries, images, or other forms were extracted:

- Aurélien Géron (O'Reilly): Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow
- Andreas C. Müller and Sarah Guido (O'Reilly): Introduction to Machine Learning with Python A Guide for Data Scientists
- tensorflow.org
- scikit-learn.org
- tslearn.readthedocs
- scipy
- pycaret
- h2o
- pytorch
- skforecast & statsmodel (For forecasting (time series) this is recommended - see notebook)
- statsforecast
- pyAF
- surprise (For recommendation systems this is recommended - see notebook)
- tensorflow-recommenders
- Keras-RL (Reinforcement Learning)
- Gym (Reinforcement Learning)
- YOLO model - Computer Vision (According to pre-trained models from Ultralytics)
- other libraries/repositories/blogs/forums linked to the previous links
- Datasets used from sites like Kaggle

**Note**: In some cases, the code may need to be modified due to changes in newer versions of the libraries, generating some incompatibility that may cause an error when executed.
**Caution**: Observed cases of potential errors in new versions of libraries

**Important**: The return of some scikit function does not return numpy format but dataframe or vice versa, generating inconsistency when using X[index] (numpy) vs X.iloc[index] or X.loc[index] (pandas), so care should be taken to manipulate the elements according to matrix (numpy) or dataframe (pandas).

--------

**Large Languaje Models (LLM)**

Use of Reinforcement Learning for Fine Tuning with LLM.
