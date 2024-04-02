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

## Data Cleaning
### Step 1. Convert the height and weight columns to numerical forms
Checked format of height and weight

![image](https://github.com/ysasamson/FIFA21/assets/145044637/0a75301f-eae5-4e15-8e88-5d7ab1170237)

Created functions to convert height and weight. Changed column names for clarity.

![image](https://github.com/ysasamson/FIFA21/assets/145044637/f488ff4c-bd79-4f8f-b47d-e5494722bb7f)
![image](https://github.com/ysasamson/FIFA21/assets/145044637/bf3619e7-368b-45dd-86e1-f14ed37c43e7)

### Step 2. Remove the unnecessary newline characters from all columns that have them

Checked which columns have newline characters

![image](https://github.com/ysasamson/FIFA21/assets/145044637/77f9d352-6af7-4e5c-8e0d-64432c6d29e3)

Removal of newline characters

![image](https://github.com/ysasamson/FIFA21/assets/145044637/157ce0b4-05e2-49f1-8b54-aacfebd63e64)


### Step 3. Convert 'Value', 'Wage' and "Release Clause' columns, which are string columns, to numbers. Example format the rows are in: '€103.5M'

Checked format of 'Value', 'Wage', and 'Release clause' columns

![image](https://github.com/ysasamson/FIFA21/assets/145044637/25094597-3e26-44d3-ad1d-406142d1a975)

Created function for converting aforementioned columns into integers

![image](https://github.com/ysasamson/FIFA21/assets/145044637/bfa8dc3b-d962-488d-8b32-c65922dc7377)

### Step 4. Remove star symbol in columns that contain it

Checked which columns have the star symbol

![image](https://github.com/ysasamson/FIFA21/assets/145044637/c4883fad-ff8c-43fc-b586-fd42989b56c6)

Removal of stars and whitespace with the star

![image](https://github.com/ysasamson/FIFA21/assets/145044637/ef310f51-6611-41f2-abba-344c5145c7ee)


### Step 5. Splitting Join date into different columns (year, month, day) and based on the 'Joined' column, check which players have been playing at a club for more than 10 years

Split join date into different columns (year, month, day)

![image](https://github.com/ysasamson/FIFA21/assets/145044637/74465341-dc44-4a05-bdfe-bf548b9d5bd9)

Created new column 'Membership_Years' 

![image](https://github.com/ysasamson/FIFA21/assets/145044637/c2f79896-9d37-48ab-a87e-038ce340d5ad)
