**EXCEL CROWDFUNDING CHALLENGE**

**(1) Project Overview and Purpose:**

Crowdfunding is a method to launch and generate buzz for new products, but success is not guaranteed. Historical information could be advantageous to discovering any tips or tricks to increase the likelihood of crowdfunding success. 
For this exercise, a database of projects will be organized, then analyzed for any hidden trends.


**(2) Dataset Description:**

The dataset is provided in a Microsoft Excel document. It contains information about each project, including supporters; donations; location(s); timelines; and category information.

Modifications were undertaken; visualizations were generated; and analysis with statistical measures were added, the result of which is stored in the Main folder within the file named "CrowdfundingBook_RRoop_04Apr2024.xls".


**(3) Data Cleaning and Preprocessing:**

Conditional formatting was applied to fill each cell in the **Outcome** column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

A new column called **Percent Funded** was added that uses a formula to find how much money a campaign made relative to its initial funding goal. Conditional formatting was applied to fill each cell in the **Percent Funded** column according to a three-color scale. 
The scale started at 0 with a dark shade of red, and transitioned to green at 100 and blue at 200.

A new column called **Average Donation** was added that uses a formula to find how much each project backer paid on average.

Two new columns, one called **Parent Category** and another called **Sub-Category**, were added that use formulas to split the Category and Sub-Category column into the two new, separate columns.


**(4) Data Visualization Techniques:**

(a) Pivot tables were generated:

(1) to count how many campaigns were successful, failed, canceled, or are currently live per category from the original dataset

(2) that can be filtered by country based on the table resulting from the modifications

(3) can be filtered by country and parent category based on the table that you created, including date/time conversions that visualize outcomes over time


(b) Line graph that visualizes projects success (counts and percentages) stratified by funding goal amount


**(5) Results and Analysis:**

The Stats tab of the Microsoft Excel (MS Excel) file contains Summary Statistics (Stats) for:

(i) projects with a Successful outcome

(ii) projects with a Failed outcome


(a) Three conclusions that we can draw about crowdfunding campaigns are:

(i) Meeting a crowdfunding goal (Percent Funded = 100%) is not a predictor of success (while surpassing your crowdfunding goal [Percent Funded >100%] enhances a successful outcome)

(ii) Audio journalism campaigns appear more successful (4/4) than other campaign types and typically exceed funding their funding goals ( >100%), at least within this dataset

(iii) Time of the year (Date Created) across Years (i.e., Month) is not a predictor of success, as most months have similar rates of success; failure; and cancellation


(b) Limitations of this dataset are:

(i)Lack of detail on potential other variables important to Outcome (e.g., size of team/organization organizing campaign; resources available to support campaign; methodologies used to undertake campaign; etc.)

(ii) Some Sub-Category descriptors could have more depth/context, for example,

(iii) Type of food truck might offer more insight (Mexican; barbecue; pizza; etc.)

(iv) Type of video games (sports; adventure; puzzles; racing; etc.)


(c) Other possible tables and/or graphs that could be generated and their value added:

(i) A graph expressing the relationship between backers_count and outcome to determine if campaign size is a reliable predictor of success (or failure)

(ii) A graph expressing the duration [calculated using Date Created (launched at) and Date Ended (deadline)] plotted against outcome might provide insight into whether shorter campaigns are more or less successful (this could help with campaign planning and logistics)

(iii) Currency conversion could precede plotting of equilibrated funding (for example, all  Euro [€] amounts) versus outcome to ascertain if a campaign’s outcome is related to pledged amount and/or country


**(6) Instructions for Interacting with the Project:**

There are two main outputs from this exercise:

(a) the previous mentioned Microsoft Excel file named "CrowdfundingBook_RRoop_04Apr2024.xls" in the Main folder, which includes the dataset; pivot tables; line graph; and stats

(b) a Microsoft Word called "Crowdfunding Report_RRoop_04Apr2024", which provides some of the information provided above in the **Results and Analysis** section


**(7) References:**
None
