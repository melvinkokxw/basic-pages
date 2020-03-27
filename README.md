# Basic pages
This repo is a personal collection of basic webpages. These webpages are meant as practice to get used to writing in HTML and CSS. Specifically, HTML5 and CSS3 are used, where there is focus on semantic markup in the html document and the separation of styling from the layout.

## BP Tribute Page
This webpage is intended to be a tribute page to Lord Baden Powell, founder of Scouting.
### Learning points
* Inserting an image into the webpage
    * Images are inherently inline, use `display: block;` in CSS to make them a block element
* Adding background colour to a webpage
    * Using a colour scheme will make the webpage look more coherent, especially with a large image
    * A brown/beige-based colour scheme was used as it is a common colour in Scouting (the colour of the 1st Gilwell Scout Group neckerchief, BP's hat etc)
* Creating anchor tags with links
* Centring HTML elements
    * On a webpage where there is no sidebar and all the content is only delivered from top to bottom, centring the article improves the aesthetics
    * Centring of block-level elements is usually done using `margin: 0 auto;`

## Survey Page
This webpage is intended to be a feedback form for the residents of a university hall of residence.
### Learning points
* Creating a form on a webpage
    * Relevant input fields can be grouped together using `div` or `fieldset`. This makes more sense semantically and also allows for better control over the placement of each item in the form.
* Styling by starting from the least specific selector to the most specific
    * In the previous project (BP tribute page), the bulk of styling was done by using id selectors
    * A more ideal way to do styling is start with the lowest specificity, e.g. tags > class > id

## Product Landing Page
This webpage is intended to be a landing page to show details about a company's products.
### Learning points
* Creating a fixed header with a nav bar
    * This is accomplished using `position: fixed;`. However, due to inbuilt browser margins, `top: 0;` and `left: 0;` have to be added to flush the bar to the top left of the webpage.
    * Two separate flexboxes were used: one to contain the company logo and the group of nav links, and another one within to contain the individual nav links
* Adding a video to a webpage
* Using `display: grid;` to create a matrix of items
    * This was used in this web page to contain the two product images and their descriptions.
    * A flexbox was initially used due to a lack of understanding that a flexbox is meant for one-directional layouts. In this case since there are both columns and rows to consider, a grid is more appropriate.
* Special note: Although scaling of the product images to fit the screen was achieved, it would be better to let the column of product overflow on a smaller screen to allow better view of the image since it is more important than the text in this context.

## Learning Resources
From The Odin Project's [curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css), specifically freeCodeCamp's [lesson materials](https://www.freecodecamp.org/learn/).

Product landing page modelled after (and intended for delivering to) an actual business, [hsi-illustration](hsi-illustration.com).

Color schemes chosen from [Color Supply](https://colorsupplyyy.com).
