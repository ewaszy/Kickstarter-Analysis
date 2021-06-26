# Kickstarting with Excel

## Overview of Project

The Kickstarter Project was executed using data from previously conducted fundraising campaigns over a wide range of categories and subcategories. The data was organized, extracted, analyzed, and illustrated with relevant visualizatons to easily identify the outcomes (Successful, Failed, or Canceled) of other fundraising campaigns conducted for the subcategory "plays" based on their Launch Date and funding Goals.

### Purpose

The purpose of this project was to gain insight about the outcomes of play campaign fundraisers based on Launch date and Goals. This was done in order to help Louise, an up-and-coming playwright, determine how these two factors fared amongst different crowdfunding campaigns after her own crowdfunding campaign for her play, "Fever", came close to it's goal within a short period of time. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Our first deliverable for this project was to create a chart displaying campaign outcomes based on their launch date. A new column named "Years" was created, and the YEAR() function was used to extract the year from the column labeled "Date Created Conversion" from the "Kickstarter" spreadsheet. Next, a pivot table was created on a new sheet named "Outcomes Based on Goals" using the following variables: 
	Filters: Parent Category (theater), Years (All)
	Columns: Outcomes (Filtered for successful, failed, and canceled; sorted in descending order)
	Rows: Date Created Conversion (months of the year)
	Values: Count of Outcomes
From there, a line chart was created to provide a graphical representation of the data produced from the pivot chart. It was titled "Theater Outcomes Based on Launch Date" and saved. 

### Analysis of Outcomes Based on Goals 

Our second deliverable for this analysis was to create a chart displaying campaign outcomes based on the goal amount. A new sheet named "Theater Outcomes by Launch Date" was created and the COUNTIFS() function was utilized to collect outcome and goal data from the "Kickstarter" worksheet for the "plays" subcategory. The SUM() function was utilized to calculate the total number of successful, failed, and canceled projects for each goal range. A line chart was created to provide a graphical representation of the data calculated we calculated from our new spreadheet, given an appropriate title, and saved. 

### Challenges and Difficulties Encountered

I did not experience any difficulties with this challenge. I was able to create the exact outcomes needed following the easy to understand step-by-step instuctions provided. Having the examples to compare my results to was extremely helpful when double checking my work. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	Two conclusions can be drawn from the Outcomes based on Launch Date graph. First, there is a greater number of successful than failed or canceled campaigns for every month. Second, successful campaigns peak during May and generally decrease throughout the end of the year while failed and canceled campagins remain relatively constant.  

- What can you conclude about the Outcomes based on Goals?

	First, we can tell that canceled campaigns are not present on the graph, indicating that there were no canceled campaigns for the subcategory "plays" for any goal amount, confirmed by the data displayed in the worksheet. Therefore, the percentage successful and percentage failed columns for each row should add up to 100%, which they do. This is confirmed through the mirrored lines representing successful and failed compaigns in the graph. However, the graph does not display the total number of campaigns for each range of goals, making it difficult to properly judge the amount of successful campaigns for each goal category without refering to the spreadsheet.     

- What are some limitations of this dataset?

	One limitation of this dataset is that it contains outcomes information for a vast set of categories and subcategories in may countries. Also, it does not tell us what type of crowdfunding the campaigns were conducting or the type of backers it attracted.      

- What are some other possible tables and/or graphs that we could create?

	We could create a table/graph representing the number of backers for each outcome. We could also create a table/graph representing the average donation based on number of backers. Both tables/graphs can be sorted by country and filtered for the subcategory "plays". 
