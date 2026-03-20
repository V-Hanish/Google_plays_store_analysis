#  Google Play Store Analysis
## End-to-end analysis of 2.3M+ app records across 33 categories using Python and Power BI to uncover what drives app success.

## Tools Used
Python (Pandas, NumPy, Matplotlib) · Power BI (DAX) · Excel · SQL

## Dataset

Source: Google Play Store dataset (Kaggle)
Records: 2.3M+ apps across 33 categories
File: [Google_playStore.csv…]()

## Data Cleaning Steps

Handled missing values in rating columns
Converted installs column from string (e.g. "1,000,000+") to numeric
Removed special characters from price column
Removed duplicate app entries
Standardised categorical variables and data types
Created new calculated columns for analysis


## Key Findings

Gaming & Communication dominate — top 2 categories account for 40% of the market with 68Bn+ installs combined
93% of apps are free — freemium is the dominant monetisation model across the Play Store
4.0+ star rating is the quality benchmark — apps below 4.0 show significantly lower install velocity
Higher review counts correlate with more installs — social proof is a stronger driver than category alone
Most apps cluster between 4.0 and 4.5 stars — competition for user satisfaction is extremely high


## Dashboard Pages
### Overview
![Overview](<img width="1534" height="904" alt="Overview" src="https://github.com/user-attachments/assets/b70e5f7d-ea7c-4fc2-91e2-cb47d08e8e92" />)

### Genre Analysis
![Genre Analysis](<img width="1542" height="911" alt="Genre Analysis" src="https://github.com/user-attachments/assets/edf90e60-1ad6-47f6-b1a5-498036e2250e" />)

### Ratings & Reviews
![Rating & Reviews](<img width="1528" height="908" alt="Rating   Review" src="https://github.com/user-attachments/assets/e01b840d-893d-4df9-a881-00b2105a6d3a" />)


## Files in This Repository


## FileDescription Google_PlayStore.csv 
Cleaned dataset used for analysis


## Python notebook 
[Play_store.ipynb](https://github.com/user-attachments/files/26132870/Play_store.ipynb)
— cleaning/EDA


## images:  Dashboard screenshots
