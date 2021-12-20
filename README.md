# WSD_medical
This is a Word Sense Disambiguation Project dedicated to medical abbreviations.
![alt text](https://raw.githubusercontent.com/BruceWen120/medal/012c5407168072ac73e3d2022fe2cea38029a6fa/figures/rs_illustration.svg)

## Models
We use BERT and Lesk Algorithm. BERT achieves the test accuracy of 87% that beats the previous state-of-the-art methods mentioned in [MeDal Paper](https://www.aclweb.org/anthology/2020.clinicalnlp-1.15)
## Dataset
The dataset used in this project is originally from [MeDal](https://github.com/BruceWen120/medal). 
We did more rigorous data cleaning and split data by labels to output the two files train_final.csv and test_final.csv.

## To run our results
Please pull our repository and config the local directory in the colab notebook. As long as you can load train_final.csv and model_12_20_3 (the model states we trained), you are all set!
