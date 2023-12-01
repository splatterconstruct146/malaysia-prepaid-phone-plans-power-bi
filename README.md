# Malaysia Prepaid Phone Plans - Power BI
A simple Power BI report used to quickly get an overview of the prepaid phone plans in Malaysia.\
Public Power BI Report Link: [here](https://www.novypro.com/project/prepaid-phone-plans-in-malaysia-report)

## Motivation
This report was created as a submission to an organization that wanted to view and compare the different prepaid phone plans available in Malaysia.\
All info can be found via a simple web search - so nothing confidential here. 

## Shortcomings
The online version of Power BI breaks the functionality of the Q&A visualization tool. The attached Power BI report file (.pbix) has the Q&A functionality in working order.\
In the online version this Q&A visualization has been replaced by a static table.

Note that since the info is found by web search, the dataset has missing values. Some info is not made available to non-customers by the telcos or very well hidden inside obsure terms and conditions documents. 

## Files 
The files found in this repository and their descriptions are as follows:
1. Prepaid Plans.xlsx: Data table holding the info used in the report.
2. perpaidplans_neutral.pbix: The Power BI report. 

## Sample Screenshots
![Screenshot 2023-12-01 212618](https://github.com/splatterconstruct146/malaysia-prepaid-phone-plans-power-bi/assets/135209633/fb0b616b-7181-42f8-a87a-0a9fc2930b2c)
Image 1: Overview page of the report. The report was made with simplicity in mind - so it only has 1 page. 

## Process
Shows the process of creating the data table and then the report.
### 1. Creating the Data Table
The various prepaid phone plans can be found via simple internet search - which was what happened here.\
Visited various telco sites to gather the most up to date data.\
Populated the data table.\

### 2. Creating Measures and Calculated Columns
After importing the data table into Power BI, some measures and calculated tables were created.\
This step was performed to ensure a fair and standardized comparison.\
For example some phone plans have a duration of 7 days while most others have 30 days. So a fair comparison is the price per day or price per 30 days.

### 3. Creating the Visuals
This step was fairly straightforward. Just apply the visuals that is best for representing the info in the data table. 

### 4. Applying a Visual Theme
Decided not to use the default theme due to it looking "cookie cutter". Decided to opt for something with a little more color; but still offered visual clarity. 
