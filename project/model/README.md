The `model` directory consists of the ipynb files which we have used for training and testing of the model. 

The file ‘glove.6B.100d.txt’ is GloVe which is used as a word embedding for all the models.

We have used 4 models namely, **CNN only, RNN only, Hybrid (CNN+RNN) baseline model and Transformer model**.

The general nomenclature followed for ipynb is,

**model_modelname_datasetname** and **model_modelname_datasetname_cross** for cross validation.


- model_CNN_FAKES.ipynb – This is the CNN model tested on Fakes dataset.

- model_CNN_FAKES_cross.ipynb – This is the  CNN model trained and tested on Fakes dataset using 5 fold cross validation.

- model_CNN_FNC_cross.ipynb - This is the  CNN model trained and tested on fnc1 dataset using 5 fold cross validation.

- model_CNN_ISOT.ipynb - This is the CNN model trained and tested on ISOT dataset.
 
- model_CNN_ISOT_cross.ipynb - This is the  CNN model trained and tested on ISOT dataset using 5 fold cross validation.


Similarly, we have the model files for RNN, Hybrid and Transformer model.

For testing the following ipynb files were used on which we got the highest scores for the evaluation metrics.

- model_CNN_ISOT_cross.ipynb -  This is the CNN model trained on ISOT. The model will be saved in `CNN_ISOT` folder.

- model_RNN_ISOT_cross_20.ipynb – This is the RNN model trained on ISOT for 20 epochs. The model will be saved in `RNN_ISOT` folder.

- model_Hybrid_ISOT_cross.ipynb – This is the Hybrid (CNN+RNN) model trained on ISOT. The mode will be saved in `Hybrid_ISOT` folder.

- model_Transformer_ISOT+3FNC – This is the transformer model trained on merged dataset from ISOT and FNC without cross validation. The model will be saved in `Transformer_ISOT+FNC` folder.
