# Housing
This is a real-life dataset consisting of housing sales prices in the city of Windsor, Ontario, Canada.
## About the Data Set

a cross-section from 1987

number of observations : 546

observation : goods

country : Canada

### Usage

data(Housing)

### Format
A dataframe containing :

price
sale price of a house

lotsize
the lot size of a property in square feet

bedrooms
number of bedrooms

bathrms
number of full bathrooms

stories

number of stories excluding basement

driveway

does the house has a driveway ?

recroom

does the house has a recreational room ?

fullbase

does the house has a full finished basement ?

gashw

does the house uses gas for hot water heating ?

airco

does the house has central air conditioning ?

garagepl

number of garage places

prefarea

is the house located in the preferred neighbourhood of the city ?

## EDA 
![image](https://github.com/user-attachments/assets/c42308cb-69a4-4860-9b2f-4bba8022e3b0)

First of all I create table from data to work efficiently.
![image](https://github.com/user-attachments/assets/1123f307-9853-4456-9fa3-b369769d2b2c)

Secondly I define type of variables.

'Price' variable is Quantitative and continious.

'Lotsize! variable is Quantitative and continious.

'Bedrooms' variable looks like Quantitative but it is categorical Nominal.

'Bathroom' , 'Stories', 'garagepl' variable are also categorical Nominal.

'driveaway', 'recroom','fullbase','gashw','airco' and 'prefarea' are categorical binary variables.

Create new column named 'ID' to work easly in frequency tables.
![image](https://github.com/user-attachments/assets/19583b7b-ff56-4559-b13a-92cdcd508d59)

Also create squared difference column that firstly, take difference between average price and observence value in the cell and square the value.
![image](https://github.com/user-attachments/assets/7d6d5b8d-69fc-4455-a0e8-a3c2417392c9)

I created this column to find varience and standart deviation.

By using Excel functions ı created descriptive statistic table.
![image](https://github.com/user-attachments/assets/0a2cba7e-9407-4136-8596-27cbccbf5e8c)

I created histogram from lotsize and change binsize from 16 to 10

![image](https://github.com/user-attachments/assets/1cea1d7a-c504-452e-9a44-fe6a06349396)
![image](https://github.com/user-attachments/assets/111dc762-1c4b-4e57-be3c-a02794bd0a79)

I also use boxplot to define outliers which have 5 outliers.

![image](https://github.com/user-attachments/assets/19bf2dca-c848-40a6-8531-8185d52bb6a8)










