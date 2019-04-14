Picnic Hackthon 2019

Intro

The model is build with Keras and uses InceptionResNetV2 as the base model.
The base model is fine-tuned and trained by using k-fold on the training set.

Steps to reproduce a .tsv file:
- The Download folder from PicNic 'The Picnic Hackathon 2019' should be unzipped in this folder.
- Add all test images inside './data/test/no_labels'
- Run the first 6 cells inside 'picnic_train_model.ipynb'. This creates all the necessary folder structure.
- Run the 'picnic_predict_model.ipynb' code. The actual model is inside the 'models' folders.

Steps to create a new model:
- The Download folder from PicNic 'The Picnic Hackathon 2019' should be unzipped in this folder.
- Run the 'picnic_train_model.ipynb' model.

Requirements:
- Python 3.5
- Jupyter Notebook

Python requirements:
- numpy
- pandas
- matplotlib
- keras
- PIL

