# What I learned in week 5

## calc-you-later
Simple calculator project where all functions are written in a JS file and exported to another JS file. Heavy on if/else statements and || operator.

## ***Document Object Model (DOM)***
DOM is a nifty way to manipulate HTML and CSS using JavaScript. All the changes made in JS will overrule anything in CSS and HTML as long as `<script>` is placed at the bottom of the HTML `<body>`. 

## this-might-be-a-domb-idea
Lots of queries with text modifications.
Introduced:

    document.querySelector('element')
    document.createElement('node element')
    element.style.cssProperty
    element.innerText
    element.src
    element.class
    element.id
    parent.appendChild(child)

Operators can be assigned to a variable. 

Note: `To modify certain element you need to query it first`

## ugly-query
Uglification with DOM. Using style on a queried element will apply it only on first child. There are several methods to target several children:

    A loop can be used to apply same style to all children.
    Using querySelectorAll children can be targeted by their index.
    childNodes operator can used on a queried parent to target it's children using their index. Note: white spaces are considered as nodes.

## domb-and-domber
DOM within functions.

## DOMmer-Party-1
<img src="https://media3.giphy.com/media/xUOwGmG2pRfFZUmdVe/giphy.gif?cid=790b7611f6b3aa893fe75202be8b39613c96747cefecd30a&rid=giphy.gif" alt="image" width='500px' style="margin-left:auto;margin-right:auto" >

## CSS Diner

    Level 11 - * Universal selector
    Level 12 - A + B One follows another
    Level 13 - A ~ B Selects all B that follow A
    Level 14 - A >  B Selects direct children
    Level 15 - :first-child selects first child of an element
    Level 16 - :only-child Selects specific child inside another element
    Level 17 - :last-child Selects last child
    Level 18 - :nth-child(A) Selects specific child

## Human Resource Machine

    Level 25 - Cumulative Countdown