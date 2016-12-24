# USDA Food Composition Visual Browser

[]

## What's our problem?
Nowaday people care about food choice and diet to keep good health.  The USDA National Nutrient Database is the standard reference for nutritional contents of food in the United States. However, it is always hard for customers to find the nutrition distribution of the food exactly and which kind of food they want based on their plan. Also comparison of nutritions among foods is more complicated. In order to solve this problem, we build a visualization system to decode the data and visualize the data sheet from USDA.


## Data Source
[USDA food composition](https://ndb.nal.usda.gov/ndb/search/list)

## How to use our system?



##  Sample Visual Browser: 
![Alt text](https://github.com/NYU-CS6313-Fall16/USDA-9/blob/master/Screenshot.png "Nutrient Visualization") 


## Features
1. Selectable food groups using check box. As and when the food groups are selected, the nutrient composition of added foods from newly added food groups are displayed using parallel coordinates.
2. A histogram of the number of foods from in each food group selected is shown next to the name of the food group.
3. A brush can be used to select the range in a nutrient. The foods are filtered dynamically based on range selection
4. Parallel coordinates can be repositioned to get an idea about their correlation with each other.
5. Ranges from multiple nutrients can be selected and foods are filtered dynamically.
6. Highlights nutrient composition of a single food item upon hovering over it. 
7. Search Box to search the food items.

## Links

* [Live Demo](https://nyu-cs6313-fall16.github.io/USDA-9/index.html)
* [Video Link] (https://vimeo.com/196914006) 
* [Project Report](https://docs.google.com/a/nyu.edu/document/d/1TMgx9vkE43MVaQPYrhZlWWjWv-eORle2dc09L0OyyZU/edit?usp=sharing)
