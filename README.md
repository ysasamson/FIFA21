# FIFA 21 Data Cleaning Project
## Objective
In this project, a messy dataset was cleaned with the following tasks completed:
1. Convert the height and weight columns to numerical forms
2. Remove the unnecessary newline characters from all columns that have them
3. Convert 'Value', 'Wage' and "Release Clause' columns, which are string columns, to numbers. Example format the rows are in: '€103.5M'
4. Remove star symbol in columns that contain it
5. Splitting Join date into different columns (year, month, day) and based on the 'Joined' column, check which players have been playing at a club for more than 10 years

## Dataset Used
This project used a dataset from Kaggle.
[Source](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring)

## Technology
Language: Python
Libraries used: numpy, pandas

## Data Cleaning
### Step 1. Convert the height and weight columns to numerical forms
Checking format of height and weight

![image](https://github.com/ysasamson/FIFA21/assets/145044637/0a75301f-eae5-4e15-8e88-5d7ab1170237)

Created functions to convert height and weight. Changed column names for clarity.
![image](https://github.com/ysasamson/FIFA21/assets/145044637/f488ff4c-bd79-4f8f-b47d-e5494722bb7f)
![image](https://github.com/ysasamson/FIFA21/assets/145044637/bf3619e7-368b-45dd-86e1-f14ed37c43e7)


