# Climate Change Prediction

### Dataset
The dataset used was <a href="https://www.kaggle.com/datasets/tarunrm09/climate-change-indicators" alt="Link to dataset" target="_blank">Climate change Indicators</a>

### How to Install

1. Download the dataset
2. Install the packages
```pip install -r requirements.txt```
3. It's not required to use python-dotenv, so feel free to choose between the two options. <br>
Option 1: Create the .env file and insert the DATASET value. It's the name of the dataset file downloaded.
```DATASET=NAME_OF_THE_DATASET_FILE.csv``` <br>
Option 2: Change the code ```data = pd.read_csv(dataset)``` to ```data = pd.read_csv(NAME_OF_THE_DATASET_FILE.csv)```
5. Enjoy it.

