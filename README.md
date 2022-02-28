# kickstarter-analysis
performing analysis on kickstarter data to uncover trends

# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis was to visualize campaign outcomes based on their launch dates and funding goals. The analysis was performed after Louise, who started 
her play *Fever*, met her goal in a short amount of time.

## Analysis and Challenges
In this project, two technical analyses were performed: Outcomes Based on Launch Date Chart and Outcomes Based on Goals Chart. Both analyses were performed in 
microsoft excel using built in functions. 

### Analysis of Outcomes Based on Launch Date
The first analysis utilized the excel pivot table function, which allowed us to create a line graph depicting the outcomes for theater kickstarter projects based on 
launch date. 
<img width="938" alt="Screen Shot 2022-02-27 at 11 30 46 PM" src="https://user-images.githubusercontent.com/99444856/155929281-4b8c1600-1b1c-41c1-8737-a0297bd3b040.png">

### Analysis of Outcomes Based on Goals
The second analysis utilized the COUNTIF() function, which counts the number of cells that meet a specificed value or phrase. For example, the specified values were 
goal brackets and their outcome (successful, failed, canceled). A line graph was then created from the proportion of the outcome to the total number of kickstarter 
projects for each respective goal bracket. 
<img width="722" alt="Screen Shot 2022-02-27 at 11 35 10 PM" src="https://user-images.githubusercontent.com/99444856/155929718-992b1215-5101-4890-95c2-264382c8079f.png">

### Challenges and Difficulties Encountered
Possible challenges that one may encounter include but are not limited to: incorrect reporting of the projects and not knowing how to efficiently perform the 
analysis by using the built in functions. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
From the analysis performed, it can be deduced that late spring (May) and early summer (June) are good months for starting projects. The failed amount of projects remained relatively consistent over the entire year. Theater_Outcomes_vs_Launchpng.png![image](https://user-images.githubusercontent.com/99444856/155930945-3daa216c-6c20-4954-bbaa-fb3fc5e30712.png)

- What can you conclude about the Outcomes based on Goals?
For the lower goal brackets, the percent of successful projects is more consistent than the results for the higher brackets. Theater_Outcomes_vs_Launchpng.png![image](https://user-images.githubusercontent.com/99444856/155931875-e97d399a-613d-4d59-aef2-4e2ab434799a.png)

- What are some limitations of this dataset?
One limitation is that the graph doesnt account for inflation across all of the years. Furthermore, regionality of the plays is lacking. Projects may fare better in different parts of the country. Also, genre of the play could impact the outcome. 
- What are some other possible tables and/or graphs that we could create?
One possible table and corresponding graph to create would be amount of time that the pledging period began and ended, perhaps the outcome of the project depends on the length of the pledging period. 
