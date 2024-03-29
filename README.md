# WSD_medical
This is a Word Sense Disambiguation Project dedicated to Medical abbreviations.
![alt text](https://raw.githubusercontent.com/BruceWen120/medal/012c5407168072ac73e3d2022fe2cea38029a6fa/figures/rs_illustration.svg)

## Models
We use BERT and Lesk Algorithm. BERT achieved the test accuracy of 87% in test_final.csv, outperforming the previous state-of-the-art methods mentioned in [MeDAL Paper](https://www.aclweb.org/anthology/2020.clinicalnlp-1.15).

## Dataset
The dataset used in this project is originally from [MeDAL](https://github.com/BruceWen120/medal). 
We did more rigorous data cleaning and split data by labels to output the two files train_final.csv and test_final.csv.

## To reproduce our results
Please pull our repository and config the local directory in the colab notebook. Then please download the [model states (model_12_20_3)](https://drive.google.com/file/d/1-YbBIvc-jbnApfxtYwIvMxwQ5FqN7nMA/view?usp=sharing) on Google Drive.
As long as you can load train_final.csv and model_12_20_3 (the model states we trained), you are all set!
