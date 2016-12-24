# USDA Food Composition Visual Browser

![screenshot](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/screenshot.PNG)

## What's our problem?
Nowaday people care about food choice and diet to keep good health.  The USDA National Nutrient Database is the standard reference for nutritional contents of food in the United States. However, it is always hard for customers to find the nutrition distribution of the food exactly and which kind of food they want based on their plan. Also comparison of nutritions among foods is more complicated. In order to solve this problem, we build a visualization system to decode the data and visualize the data sheet from USDA.


## Data Source
[USDA food composition](https://ndb.nal.usda.gov/ndb/search/list)

## How to use our system?
* First, the middle polygon graph is the main graph. Each line that forms a polygon is a food. The different color represents different food group.
![1](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/imgs/screenshot1.png)
* The color of the food group is defined on the right side. There are 25 group to categorize the food.
![2](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/imgs/screenshot2.png)
*   If user do not have particular interest in any food. We suggest he can click on any of the food group on the right. Once he select click on a food group, the selected food group will be highlighted in the main graph as shown below. In this graph, the Breakfast Cereals group is clicked, we can see the general nutrient distribution in this graph. Tha is, most of the breakfast cereals product is, high carbohydrate, and high water with medium sugar, fiber, fat and protein.
![6](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/imgs/screenshot6.png)
* The left side is filter section. Each scroll bar is a filter for a certain nutrient. User can use the filter to limit the number of polygons shown in the main graph. 
![3](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/imgs/screenshot3.png)
* In the lower image, there is a food list in the left. The food in the food list is corresponding to polygon shown in the graph. If user select a food in the list, the information for detail nutrient composition will be shown with a pie chart. 
![4](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/imgs/screenshot4.png)
* Also, this selected food will be shown in the right scatter plot and highlighted with bigger circle enclosed with black border. Two nutrients can assigned to the x-axis and y-axis to see the relationship between these two nutrients. The circles in the scatter plot is corresponding to the food list and also the main plot while color is mapped with the legend in the upper right.
![5](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/imgs/screenshot5.png)

## Links
* [Live demo link](https://ginli.github.io/USDA-14/visual-browser-1.0/dashboard-page/)
* [Video demo](https://vimeo.com/196918216) Also available for [download](https://github.com/NYU-CS6313-Fall16/USDA-14/blob/master/video-demo.mp4)
* [Final project report](https://drive.google.com/file/d/0B0md3S9CvhRRLXdxZGtVWEg0Vjg/view)
