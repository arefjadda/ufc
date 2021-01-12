# UFC
#### This is my BrainStation Capstone project on the UFC Match Predictor.

The data was imported from kaggle from [this](https://www.kaggle.com/mdabbert/ultimate-ufc-dataset) link. Since it is a small dataset it is included in the data folder. The following steps need to be taken chronologically to get through the entire project:

1. First make sure that you have all the needed packages mentioned in the **requirements.txt** file installed in your conda environment or wherever you plan on opening the python notebooks. Tensorflow did have some issues in that environment, so use the **dlrequirements.txt** for the neural network notebook. It is recommended that you set up a new environment and install everything there to avoid any unwanted problems with the base packages.
2. Open the **Data Cleaning.ipynb** file to start the cleaning process. This file is where all the data preprocessing and feature engineering was done.
3. The **Machine Learning with scikit-learn.ipynb** file is where all the machine learning models in scikit were tested and the hyperparameters were optimized. The **Deep Learning with ANN.ipynb** is the other machine learning file that explores artificial neural networks in tensorflow.

***Note***: The files included do not contain the entire cleaning and testing processes. They are solely the cleaned up final versions of those steps. In fact, most models that were tried are not included here since they gave unreasonable or irrelevant results.

#### If you have any further questions about my work here you can reach out to via my [LinkedIn](https://www.linkedin.com/in/arefjadda/) account.