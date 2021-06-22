# Kickstarting with Excel

## Overview of Project
- In this Project it contains the data of different types of Tv shows,web series,videos etc in different categories with launched date and country and also with Pledged and goal amounts and with outcomes of Successful,failed,Canceled and live.

### Purpose
- The main purpose of this data set is to analyse different types of using different functions,graphs and we can obtain the outcomes based on different criteria like launch date, goal,pledged,parent category.

## Analysis and Challenges
- I Performed two types of analysis using the provided data, one is Theatre Outcomes by launch date and the other is Outcomes based on goals,The Challenges I experienced in Theater outcomes is in creating year column and I overcame this with by converting  date created conversion column, I created this column by converting epoch value of launched at column using (launched at column/86400)+Date(1970,1,1) this formula.And the second challange I overcame is implementing countifs function. 

### Analysis of Outcomes Based on Launch Date
- In Theater outcomes based on Launch date get the pivot table by filtering parent category to theater and have the each month successful,failed,canceled outcomes, In may and june the successful outcomes are more. 

### Analysis of Outcomes Based on Goals.
- While Analysing the outcomes based on goals data, I figured out that there are no canceled outcomes in category "Play" and the successful outcomes are more in 1000 to 4999 goal range and success outcomes are 0 in 45000 to 49999 range.

### Challenges and Difficulties Encountered.
- Challenges and difficulties I encountered is creating years column For that I created date created conversion column from launched at column and the other difficulty I faced is using Countifs for goal ranges.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   - The two conclusions based on launc date worksheet the theater  is started from 2009 onwards and overall theater success outcomes are more than failed and canceled outcomes.

- What can you conclude about the Outcomes based on Goals?
 - The two conclusions beased on goals are the canceled percentage is zero and success outcomes are more in 1000 and 4999 range out of all other ranges.

- What are some limitations of this dataset?
  - The limitations of this dataset are there are no viewership ratings and no competetive programs ratings and international revenue. 

- What are some other possible tables and/or graphs that we could create?
   - Possible tables and graphs we could create are outcomes based on category/Subcategory.
