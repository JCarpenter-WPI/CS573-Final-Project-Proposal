# CS573-Final-Project-Proposal

## Data

The data I propose to visualize for my project comes from three sources:  National Association of Corporate Relations Officers [NACRO](https://nacrocon.org/) membership data;  NACRO member survey data;  [College Scorecard](https://collegescorecard.ed.gov/data/) data.  The data from these sources will be merged for different parts of the project.

## Prototypes

I’ve created two proof of concept visualizations of this data. 

The first one is a map that shows the location of institutions that NACRO members are affiliated with and the number of members at each institution.  

[![image](https://user-images.githubusercontent.com/54547762/66050217-c6d02f00-e4fa-11e9-801d-dd29323218d3.png)](https://beta.vizhub.com/JCarpenter-WPI/2766fc02e0c64090a49dfaba9069d36d)

The second one is a bar chart showing the diversity of corporate relations office types by number of NACRO members.

[![image](https://user-images.githubusercontent.com/54547762/66050276-eb2c0b80-e4fa-11e9-9468-8b53ac9199ec.png)](https://beta.vizhub.com/JCarpenter-WPI/972b7672955b4792b0e115b459068c85)

## Questions & Tasks

The following questions will drive the visualization and interaction decisions for this project:

 * Who are the members at institutions near me?
 * Who are the members at institutions similar to mine in terms of size, public/private, and Carnegie Classification?
 * Who are the members in my region?
 * How do price and outcomes relate to the level of corporate engagement?
 * What is the diversity of corporate relations office types represented by NACRO members?
 * Are there geographic patterns to the level of corporate engagement?
 
 These questions translate into the following tasks and sub-tasks:
 
 1.  Update map of membership by institution
 
 * create tooltip showing list of members and contact info by institution
 * create menus for for organizational characteristics such as size, public/private and Carnegie Classification
 * color code regions
 * create functionality to display list of members when users click on region
 * create zoom functionality to more clearly see instititutions that are close to each other (e.g. Boston area)
 
 2.  Create price and outcomes chart
 
 * create side by side scatterplots of price and outcomes by level of corporate engagement
 * create tooltip to show name of institution when hovering over a point on the scatterplots
 * create functionality to select a point on one plot and highlight the same institution on the other plot
 * create menu to search for name of institution and highlight the corresponding points for that institution on plots
 
 3.  Update chart of diversity of office types
 
 * add menus for orgnizational characteristics such as size, public/private and Carnegie Classification
 
 4.  Create map of level of corporate engagement
 
 * create map with marks indicating (either by size or color) the level of corporate engagement
 
 5.  Wish list:  Create fancy plots of corporate engagement
 
 * explore possibility of creating box plots or violin plots
 

## Sketches

The sketch below shows the relationship between the number of companies present on campus (a measure of corporate engagement) and price and outcomes.  Putting these two visualizations next to each other allows a user to select an interesting point on one of the charts and  see where that same institution is located on the other chart.

![image](https://user-images.githubusercontent.com/54547762/66050336-09920700-e4fb-11e9-9d38-dd456d65827b.png)

## Schedule of Deliverables

10/2 Task 3
10/9 Task 4
10/16 Task 1
10/23 Task 2
10/30 Task 5 and put everything together


