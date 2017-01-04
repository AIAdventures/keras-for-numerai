# Keras for numerai

Contains starter code for participation in the [Numerai](http://numer.ai) competition  using deep learning framework, [Keras](http://keras.io)

## 1. Configuration
Define your Neural Network Architeture in `train.py` 
Download data from [Numerai](http://numer.ai)
Remove `t_id` column in `numerai_tournament_data`  remove `feature` column in `numerai_training_data`
Put data in `/data` 

Dependencies
- `pip install requirements.txt`

Set variables training
 - `validation_split=0.3`, Sets 30% of training data for testing
 - `shuffle=True`,  Set to `True` if you want  to shuffle data before each epoch
 - `nb_epoch=50`,  Number of epochs you want your neural net to train
 - `batch_size=5000` Number of batches you would like to use during training

## 2. Usage
Train the network `python train.py`

Create predictions `python predict.py` predictions are in  `/predictions/predictions.csv`

## 3. Performance details
Varies by architecture used & Numerai data released each week 


[Wired Article on Numerai](http://)






