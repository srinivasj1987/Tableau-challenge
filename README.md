# Tableau Homework - Citi Bike Analytics

## Data Source
Monthly CSV files (Jan 2022 - Dec 2022) were collected from [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

## Visualizations
https://public.tableau.com/views/NY_bike/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link


## Data Preparation
The csv were combined using a python code. This code is present in the folder data under combining_csv.ipynb. This generates a data that is close to 980k records. The level of information is sufficient to understand trends.

## Analysis
### 1. Total number of rides
People seem to ride more bikes in the summer than in the winter. The possible reason could be that people are not willing to ride outside in winter due to the cold weather.
December 2022 had the lowest number of records, while August 2022 had the highest number of records.
The maximum increase in % for number of rides was seen for the month of April and the lowest % was December. This may be largely due to the weather.
<img width="1463" alt="Screenshot 2023-09-04 at 19 41 52" src="https://github.com/srinivasj1987/Tableau-challenge/assets/132161799/046471ed-4aa2-4340-9fed-2f4bafd582fb">

### 2. Top/Bottom Ten Stations
Top ten stations for both ending and starting a journey are Grove St PATH and Hoboken Terminal. Locations near Train stations have high volume of trips starting and ending indicating that people use this service to connect to railways.
<img width="1463" alt="Screenshot 2023-09-04 at 19 42 21" src="https://github.com/srinivasj1987/Tableau-challenge/assets/132161799/bc074039-63d3-434f-aefa-83c74ef614b2">

### 3. Peak Hours
Rush hours(8:00 and 17:00-18:00) seem to be the peak hours for riders.
In the summer, more people ride bikes in the evening than in the morning, but in the winter, more people ride bikes in the morning than in the evening.
<img width="1463" alt="Screenshot 2023-09-04 at 19 42 37" src="https://github.com/srinivasj1987/Tableau-challenge/assets/132161799/6bc9c233-6785-496e-9c20-e5ec435b0051">

### 4. Days of the week
In Summer, Monday to Saturday sees high cycle volume while sunday sees the lowest, Saturday being the highest suggesting that the lot of people like to travel on Saturday being a weekend. Where as in winters, the Weekdays sees more traffic than Weekends suggesting that cold weather plays a role in people going out on a Saturday. 
<img width="1463" alt="Screenshot 2023-09-04 at 19 43 00" src="https://github.com/srinivasj1987/Tableau-challenge/assets/132161799/5515435e-a53a-4308-8e8c-7cd555950e8c">

###5 . Bike popularity and Member vs Non-member usage.
Of the 3 types of bikes provided, classic, docked and electric, the most popular is the classic bike. The Docked bike is used solely by non-members and not by members. The Electric bike is used by both members and non members but it isnt as popular as the classic bike. Members use the citibike service more than non-members.<img width="1463" alt="Screenshot 2023-09-04 at 20 07 06" src="https://github.com/srinivasj1987/Tableau-challenge/assets/132161799/d527ac4b-5884-49cb-af42-7262b737cd69">


