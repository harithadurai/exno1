# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
import pandas as pd
data=pd.read_csv('D:Data_set (1).csv')
print(data)

<img width="815" height="826" alt="image" src="https://github.com/user-attachments/assets/644ec88e-42f8-434e-a1e7-b1d6d4e709ca" />

import pandas as pd
data=pd.read_csv('D:Data_set (1).csv')
print(data)
df=pd.DataFrame(data)
df.describe()

<img width="824" height="368" alt="image" src="https://github.com/user-attachments/assets/1874b7c5-be89-4ee1-9a6a-0d22c9b2a7bb" />

import pandas as pd
data=pd.read_csv('D:Data_set (1).csv')
print(data)
df=pd.DataFrame(data)
print(df.isnull())

<img width="685" height="569" alt="image" src="https://github.com/user-attachments/assets/27591f3f-f43b-4f4d-bbfc-33802b0671be" />

import pandas as pd
data=pd.read_csv('D:Data_set (1).csv')
print(data)
df=pd.DataFrame(data)
print(df.isnull().sum())

<img width="300" height="225" alt="image" src="https://github.com/user-attachments/assets/47bd73da-7cdc-430b-8f2f-e733a72af16f" />

import pandas as pd
data=pd.read_csv('D:Data_set (1).csv')
print(data)
df=pd.DataFrame(data)
df.info()

<img width="404" height="272" alt="image" src="https://github.com/user-attachments/assets/57281b00-53f3-4b73-8b6e-5ae2170d7549" />
