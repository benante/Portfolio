Based on the <a href="https://github.com/benante/agency-website"> Valour Academy project</a>

## 1. Structure a site using semantic HTML to aid accessibility
Different semantic elements were used aid accessibility:

<img src="https://github.com/benante/Portfolio/assets/63957194/f5f2db1d-f0c9-47bb-afe7-9f54606b4b85" width="500"  />

```<header>``` includes a ```<nav>``` element that contains navigation links. 

```<main>``` on the other hand is divided by different ```<section>``` elements which also includes ```<h1>``` and ```h2``` headings, ```<p>``` paragraphs, and ```<li>``` list elements 
## 2. Ensure a web page is readable for screen readers
To ensure the web page is readable for screen readers, the following practices have been implemented:

ARIA attributes have been used to provide additional accessibility information. For instance ```<aria-label>``` has been used to provide labels for navigation links and buttons.

Images have been provided with appropriate alternative text using the ```<alt>``` attribute, allowing screen readers to describe the images to visually impaired users.

The website was run through Accessibility Checker and passed the test.

## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

<img src="https://github.com/benante/Portfolio/assets/63957194/a0e746bb-9caa-465c-85a5-1891b0a5a9bd" />

## 4. Use various tools to check that our website meets accessibility criteria

## 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes
Mobile and tablet screen have the same properties here, the layout shows a significant change only when on desktop size

<img src="https://github.com/benante/Portfolio/assets/63957194/fe30f8ef-ce3e-4d83-b1a9-8703c9238d13" height="300"/>

## 6. Demonstrate a mobile-first approach to building a website
After an initial quick draft on Figma the website was build for mobiles first, then media queries were added for responsiveness for larger screens

## 7. Use CSS variables to apply repeated colours to HTML elements

<img src="https://github.com/benante/Portfolio/assets/63957194/27549926-bcce-406e-9775-073dc217a76f" height="300"/>

## 8. Use CSS Flexbox to style children in a single-direction layout (ie a row or a column)

<img src="https://github.com/benante/Portfolio/assets/63957194/8e9142c1-ebb3-4c63-91f0-ae9ed0dbdd03" width="300"/>

## 9. Use CSS Grid to style children in two-direction layout
The ```.programme``` class is used to create a grid layout with three columns and a gap of 2 pixels between grid items. This allows the children elements to be positioned in a two-dimensional grid layout

<img src="https://github.com/benante/Portfolio/assets/63957194/739bb97f-1b27-429a-ba23-9613ec036bb5" width="300"/>

## 10. Ensure our Git commit history tells a coherent story
Being the first project done with another collaborator there is a different style on committing, yet it seems like a good start

<img src="https://github.com/benante/Portfolio/assets/63957194/7f430fe2-ec1e-4bb9-a158-2426e5400dc2" height="300"/>

## 11. Use the appropriate input types in HTML forms for gathering different types of information
The ```<form>``` includes elements such as ```<input>``` with multiple different ```<type>``` ("text", "textarea", "email", "radio") and a ```<select>``` element used to create a dropdown menu, allowing the user to select their preferred trainer from the available options. The name="trainers" attribute is used to identify the selected value.

<img src="https://github.com/benante/Portfolio/assets/63957194/e308435f-d2c2-448e-99bc-a79c279b5831" height="300"/>


