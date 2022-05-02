# Simple-Website-Template
This is an idea I got from some one else and I absolutely loved so I thought I should remake it in my own style

- add animation that is on top of image when it is in mobile version 

# Colors
background color: #fdfdfd
text color: #222222
Link Colors: #0876AD
Hover link: #ABCDE6
___
# TABLE OF CONTENTS
- [How to Get Started](#how-to-get-started)
- [Must Know](#must-know)
    - [Text Manipulation](#text-manipulation)
    - [Color Manipulation](#color-maniplation)
- [Project Folder](#project-folder)
    - [Code To Look For](#code-to-look-for)
- [How to Set Links](#how-to-setup-link)
___
# How To Get Started
This website is meant to be simple and easy to use. I assume you don't know much about how website and might not be able to build your own so I will make this easy so you can this work for your project.
## Must Know
For any sort of changes to images or names you will need to make sure that the browser knows where it is looking for the image or what ever source you are trying to show on your page.
You also what to make sure if you are adding any sort of image you add it to the *resources folder* so that you know where to look for this image or resource.
### Image Source
```html
<img url="resources/your-image">
```
### Text Manipulation
All **Bold Text** has a small class called bold. Anything that you might want to make stick out you can add this class to and you will be able to easily add a nice bold blue color text.
### Color Maniplation
For all colors you can easily switch out the colors to fit your style by going to the *root.css* files and there you will see the root colors and even all the text manipulation you want. 
For the colors you want to simply change the value for a color you want.
```CSS
:root{
    --background-color: #fdfdfd;
    --text-color: #222222;
    --Link-colors: #0876AD;
    --link-hover: #ABCDE6;
}
```
These will be the ones you want to change if you want to change some colors in your website. What ever floats your boat.
## Project Folder
In the project folder there will be a template page so if you add ned projects to your website you are able to duplicate this file and easily add it to the grid.
Once you duplicate the file you can go in and rename the duplicated file. After its been renamed you can go in and begin to change any text.

### Code to Look for 
Most changes will be from heading, maybe groups of text of some simple link you will see these sections of code as these following tags
```html
<h1> heading 1 tag </h1>
<a href="[add url link here]"> link tag </a> <!-- this is where you change some links-->
```
## How to Setup Link
In the home page I have place a main link for the projects page but also smaller links for your top projects. All you will need to do is change the "#" to the url or the link you want it to go to.

EXAMPLE:
``` html
<a href="about-me.html">About Me</a> 
```   