# Snake Classifier

Machine learning proyect to classify 10 breeds of snakes :snake:

|Scientific name|Coloquial name|
|--|--|
| Thamnophis sirtalis | |
| Storeria dekayi | |
| Pantherophis obsoletus | |
| Crotalus atrox | |
| Nerodia sipedon | |
|Pituophis catenifer| |
| Pantherophis alleghaniensis | |
| Agkistrodon contortrix | |
| Diadophis punctatus | |
| Nerodia erythrogaster | |

  
  

## Notebooks:

  

### 01_data_exploration_original_dataset :

  

This notebook is focus on explore the original dataset from [snakeclef2021](https://www.aicrowd.com/challenges/snakeclef2021-snake-species-identification-challenge).

-  ***SYSTEM  REQUIREMENTS*** :
	- [ ] Requires a 64-bit processor and operating system
	- [ ] **OS**: Windows 8.1 64-bit or Windows 10 64-bit
	- [ ] **Memory**: 8 GB RAM
	- [ ] **Storage**: 140 GB available space

  
  

### 02_data_pre-processing :

This notebook focus on preprocessing data that will be use for test and training.

-  ***SYSTEM  REQUIREMENTS*** :
	- [ ] Requires a 64-bit processor and operating system
	- [ ] **OS**: Windows 8.1 64-bit or Windows 10 64-bit
	- [ ] **Memory**: 8 GB RAM
	- [ ] **Storage**: 140 GB available space

  

### 03_data_exploration_pre-processed_dataset :

This notebook is focus on explore pre proccesed dataset from [Snake Breeds](https://www.kaggle.com/deividt/snake-breeds) in order to check if data was correctly pre-processed and it's ready for train the model.

  

-  ***REQUIREMENTS***:
	- [ ] Run notebook in google colab

### 04_model_arquitecture_and_training :

  

This notebook focus on train and validate machine learning model.

  

-  ***REQUIREMENTS***:
	- [ ] Run notebook in google colab

## Datasets

  

-  **[Snakeclef2021 dataset](https://www.kaggle.com/deividt/snakeclef2021)** : Taken from [SnakeCLEF2021 - Snake Species Identification Challenge](https://www.aicrowd.com/challenges/snakeclef2021-snake-species-identification-challenge)

  

-  [**Snake-breeds**](https://www.kaggle.com/deividt/snake-breeds) : Pre-proccessed dataset of Snakeclef2021 Dataset

  

## data_csv folder

Quick access to the .csv files from each dataset.

- **data.csv** : Contains the properties of each image. Like name,id,country, image location etc.

- **preproccesed_data.csv**: Contain three properties: the snake name, id and image location.

  

## model folder

Contains the best .tflite model for deployment