## Website Performance Optimization portfolio project
This project was made under the Website performance optimization topic under the Udacity Front-end Nanodegree.

## To run the project :
You can visit the website published at [here](https://rimildeyjsr.github.io/Udacity-Front-end-Nanodegree---Optimized-Webpage/).
Alternatively, you can clone or download the zip and run it in your browsers. 

*The website received a score of 95/100 for mobile and 96/100 for desktop for PageSpeed Insights

## Optimizations made in index.html (as suggested by pagespeed insights) 
1. style.css was included in a style tag to remove render blocking css.
2. media was added to print.css
3. a font loader was used to load the google font
4. All javascript scripts were changed to async to load them asynchrononously
5. the images were optimized

##Optimizations made in views/js/main.js for pizza.html
1. changePizzaSize() simplified  to accomodate only percentage unit. Consequently, repeated queryong reduced and stored in one variable. Also repeated calculations between px and percentage eliminated. Unnecessary functions and calculations eliminated with only required code to make the slider work correctly.
2. Simplified repeated calculations in updatePositions() by storing them in arrays and variables and split calcuations into two loops. Reduced the number of pizzas created to eliminate unnecessary execution of loops and hence reduce time.

