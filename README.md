# Mini-Project2
A CSS Cheatsheet
![Project 2 Screenshot](/assets/images/project2screenshot.jpeg)

# Contents
* This webpage features a grid of 12 CSS code snippets that can be used to create a flexible grid system, as well as some of the styling 
for things such as gradient backgrounds, card header positioning and a glow on hover.

# Features
* Upon hovering over a card, it will have a slight internal glow. This will also apply to the card header if you hover specifically over it.
* There is also a transform property which will make the card and card header "grow" on hover to give strong visual feedback on mouse location and selected card.
* There is a user.select property styling the code within the card, allowing the full snippet of code to be selected with a single click
* The grid will change layout depending on your device (or width of window).
* For desktop (or any window than 993 pixels and higher):
  - The grid will be 3 wide and 2 tall
* For tablet  (or any window between 769 and 992 pixels):
  - The grid will be 2 wide and 3 tall
* For mobile (or any window 768 pixels and below):
  - The grid will be 1 wide and 6 tall 

# Styling
* All colors are saved as variables in the :root of the CSS file, allowing for easy changing of color scheme

# Editing
* More cards can be added within the ```<section id="cardGrid">```using the following HTML format:

```
<article class="card" id="cardNameCard">
    <h2 class="cardHeader" id="cardNameHearder">
        *Card Title*
    </h2>
    <p class="cardDescription" id="cardNameDescription">
        *Card Description*
    </p>
    <div class="cardContent" id="cardNameContent">
        <p class="cardCode" id="cardNameCode" 
            <pre>
.your{                      *note, for code to style as expected, put it at the start of the line
    code: goes (here)
}    
            </pre>
        </p>
    <div>
    </article>
```

  
