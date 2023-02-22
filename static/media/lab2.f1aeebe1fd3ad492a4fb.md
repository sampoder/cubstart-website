# Random Joke Generator

Welcome to Lab! Today, you will be creating a random joke generator, similar to the video below! 

<div style="position: relative; padding-bottom: 53.59375000000001%; height: 0;"><iframe src="/assets/lab2/lab2demo.mp4" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

<strong>Note:</strong> Lab is meant to be collaborative! Introduce yourself to the people next to you and work on this lab with 1 or 2 other people!

## Setting up your Files
<ol>
  <li>Download the skeleton for the homework <a href="./assets/lab2/lab2-skeleton.zip" download>here</a>. </li>
  <li>Unzip the file.</li>
  <li>Run your text editor of choice. </li>
  <li>Open the lab 3 zip folder. We will only be editing <strong>index.js.</strong></li>
</ol>

## Instructions

Briefly look through all of the files and read the comments. Take a look at <strong>index.js</strong> line 2. We created an array of jokes named <strong>jokesArray</strong>. Everytime we click the button, we want to select a random joke from that array by indexing into <strong>jokesArray</strong>. 

### <strong>Task 1</strong>
Fill in the <strong>getRandomInt</strong> function body. 

_<strong>Hint:</strong> You will need to use Javascript’s built-in math.Random() and math.Floor() functions. [Here](https://www.w3schools.com/js/js_random.asp) is a helpful link, please check it out!_

### <strong>Task 2</strong>
Fill in the <strong>replaceJoke</strong> function body. 

_<strong>Hint: </strong> <strong>randInt</strong> should be a random integer greater than or equal to zero and less than the length of <strong>jokesArray</strong>. What function do we need to call for this to happen?_

_<strong>Hint:</strong> <strong>randJoke</strong> should be a string from jokesArray at index <strong>randInt.</strong>_

_<strong>Hint: </strong> For line 30 in <strong>index.js,</strong> we want to modify the content of our HTML file so anyone viewing our site can see the joke! You will need to get an HTML element with a specific id (look through your HTML file to figure out what the id is called!) and use the innerHTML property. This [link](https://www.w3schools.com/js/js_htmldom_html.asp) is super helpful!_

### <strong>Task 3</strong>

_<strong>Hint: </strong> Check out this [link](https://www.w3schools.com/jsref/met_document_getelementbyid.asp)._

### <strong>Task 4</strong>

_<strong>Hint: </strong> Here is another [link](https://www.w3schools.com/js/js_htmldom_eventlistener.asp). If you get really stuck, highlight the line below._

<span style="color:white">button.addEventListener(“click”, replaceJoke);</span>

## Congrats on completing Lab 2!
Try out your joke generator by clicking on the index.html file on your computer! Add some of your most knee-slapping dad jokes to the array if you’d like!
