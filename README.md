# Random Imager

---
Title: Random Imager<br>
Type: Lab <br>
Duration: 45 - 60 mins<br>
Creator: Thom Page <br>
Topics: DOM events and manipulation<br>
Adapted by: Taylor Darneille

---

Make a directory `random_imager`  with the following files:

* index.html
* app.js
* style.css

![](https://i.imgur.com/89MLBWz.png)

* Using javascript dom manipulation, make a div with the text "Add random image". Add a class to make the div square (100 x 100). Give it some color.

* The div should have `cursor: pointer` in its CSS, so that when the user hovers the cursor over the div, the cursor turns into a pointer thing.

* Make an array of six image urls in your js file. (strings)

* Make it so that when you click the "Add random image" div, one random image from your array will appear on the page.

* Make it so that each image is re-sized to the same proportions as the square div (100 x 100). Or, you could use Google images -> Tools -> Size to source images at the size you want.

* Make it so an image is added rather than replaced.

* Make it so the images are added horizontally.



## HUNGRY FOR MORE

* Make it so that when you click on one of the added images, it will be removed from the page.

* Each added image can run the same function to achieve this goal.

* Add an input element that takes a new URL that allows you to add a new URL string to your array


## EVEN HUNGRIER

1. EXTRA RESEARCH CHALLENGE: Add an input box and a button to your labs. When the button is clicked, grab the value of the text inside the input box, and use that value as an argument in your `generateCheckerBoard(NUM)` and `generatePyramid(NUM)` functions from Saturday's lab.

2. Add two input boxes (name and address) and button to the virtual rolodex. Make it so when the user clicks the button, the name and address are added to the data array and the page repopulates the rolodex.
