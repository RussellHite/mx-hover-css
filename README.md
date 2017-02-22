# mx-hover-css
hover.css file converted for use in Mendix
http://ianlunn.github.io/Hover/

## Prerequisites
For easiest implementation of this or any other icon font it is reccomended you install the Vanilla theme when you start to style your applicaton.
https://appstore.home.mendix.com/link/app/2681/Mendix/Vanilla-Theme

## Configuration
Here are the steps to incorporate this file into your project. 


### Step 1
Copy and paste the _hover.scss file into the following folder your_project_folder/theme/styles/sass/lib/components
### Step 2
Open the lib.scss file under your_project_folder/theme/styles/sass and under the bottom add the following line:
```
@import "components/hover";
```
to include the _hover.scss file partial into the outputed css file

## Basic usage
The Hover classes are best used when you want to call attention to a button or element on a page when you mouse over it. Below are some quick instructions on how to use them on your project.   

1. Add the class that corresponds to the effect you want your element to show such as `hvr-pulse-grow` 


For more details on how to use the classes included, check out:
http://ianlunn.co.uk/articles/hover-css-tutorial-introduction/