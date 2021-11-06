<h1 align="center">Foodie Family - Recipe Sharing Website</h1>

![Responsiveness Screenshot](/assets/images/responsive-image.png)

**Live Site:**
[High/Low Game Website](https://samanthabooth81.github.io/foodie-family/) - TBC

**Repository:**
[High/Low Game Repository](https://github.com/SamanthaBooth81/foodie-family)

# About
High / Low is a game of chance involving, as the title suggests, making a guess whether the following number will be  higher or lower than the one displayed. This game is targeted at those who enjoy simple arcade style games that are based on decision making using probability as a foundation. 

The use of JavaScript enables the random selection of two numbers, one which is displayed and a second which is hidden. These two numbers change everytime a correct choice is made. JavaScrupt is also used to check the user answer against the correct answer and incrementing the score if correct or ending the game if incorrect. 

# Table of Contents

[User Experience](#user-experience)

[Features](#features)

[Features to be Implemented](#features-to-be-implemented)

[Technologies Used](#technologies-used)

[Testing](#testing)

[Validator Testing](#validator-testing)

[Performancce Testing](#performance-testing)

[Bugs Found](#bugs-found)

[Deployment](#deployment)

[Credit](#credit)

[Acknowledgments](#Acknowledgments)

# User Experience
## User Stories
- As a visitor who enjoys chance games 
    * I want to play a simple game that is also challenging in its range of choice. 
    * I want to intuitively understand how the game works. 
- As a visitor who wishes to be entertained 
    * I want a game that is catchy and addictive without being too difficult. 
    * I want a game that I do not have to keep up with a story line.
- As a visitor who needs something to break up their day
    * I want to easily understand the rules and layout of the game without additional instructions needed.
    * I want to intuitively understand how the game works. 

## Design

### Colour Scheme
I have chosen to use pops of bright colours on a dark background to tie in with the theme of a simple arcade style game. The colours are used mainly to point the users attention to the area of play. 

 The colors used are #38B6FF (a light blue) for the buttons, #FC52FF (a neon pink) for the button borders and #7BFF2B (a neon green) to highlight the higher and lower buttons on hover as well as for the dotted border around the game area. 
 These were chosen using a square complimentary approach of the color theory generated by [Adobe Color Wheel](https://color.adobe.com/create/color-wheel) .

<img src="assets/images/adobe-color-wheel.png" height="150px"> 

### Typography

The main font used was 'Acme', Sans-serif. I chose this font as I thought it's playfulness suited the game I was creating but was still easily readable. 

<img src="assets/images/acme-google-fonts-min.png" height="40px">

I also used the fallback fonts of:
- 'Oswald' sans-serif, 

 <img src="assets/images/oswald-google-fonts-min.png" height="40px">
 
 - 'Urbanist' sans-serif

 <img src="assets/images/urbanist-google-fonts-min.png" height="30px">

### Wireframes

- The following wireframes were created in Balsamiq. They were followed closely to acheieve the final outcome, however, there was a change in the header and I moved Game Instructions into a popup window to declutter the page. 

<img src="assets/images/load-page-wireframe-min.png" height="305px"> 

<img src="assets/images/incorrect-answer-wireframe-min.png" height="300px"> 

- The below is a screenshot of the final page layout 

<img src="assets/images/game-overview.png" height="250px"> 


### Other Details
- Favicon

# Features
- Homepage
- Recipe Page 
- Login/Sign Up
- Add New Recipe Page
- Navigation 
- Footer 

## Features to be Implemented

# Technologies Used

## Languages Used

[HTML5](https://en.wikipedia.org/wiki/HTML5)

[CSS](https://en.wikipedia.org/wiki/CSS)

[JavaScript](https://en.wikipedia.org/wiki/JavaScript)

## Frameworks, Libraries and Programmes Used 

[GitHub](https://github.com/) - Used to hold a repository of my project and deploy the live website to Git Pages, making it public.

[GitPod](https://gitpod.io/workspaces) – Connected to GitHub, GitPod hosted the coding space, allowing the project to be built and then committed to the GitHub repository. 

[Google Fonts](https://fonts.google.com/) - Used to import 'Gotu' and 'Open Sans' fonts into the style sheet. 

[Favicon Generator](https://favicon.io/favicon-converter/) - Used to convert a .png file into a Favicon.

[Canva](https://www.canva.com/) - Used to decide inital colours for the project.

[Bootstrap Framwork](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Used for quick CSS stylling throughout.


# Testing

## Functionality 
The game was tested using console.logs to ensure the code was calculating the correct answer and incrementing/decreasing the score as it should. 

To test the site the usability and the functionality of the game I also shared the deployed site with a few friends and family members of different ages to confirm ease of use. As far as they could see there weren’t any issues with understanding how to play the game, the functionality of the game and the layout on their screens. Each button worked as expected and the alerts helpful in directing the user. 

## Compatibility Testing
Devices Tested with:
- Apple MacBook Pro 13”
- Razer Blaze Pro 17.3”
- iPad OS 14.6
- Apple iPhone X
- Apple iPhone XR Plus
- Samsung S10+
- Samsung Galaxy Z Flip3 

Web Browsers tested on:
- Google Chrome
- Safari
- Microsoft Edge

Chrome DevTools was also extensively used to test responsiveness. 

# Validator Testing

- HTML

No errors were returned when passing through the official W3C validator.

- CSS

No errors were found when passing through the official (Jigsaw) validator.
Warnings were flagged for background colour of the Play Button as it matched the background colour of the document but it is required as without a set background colour for the image the background displays white for the button. 

- JavaScript

No errors were found when passing through [JS Hint](https://jshint.com/). 

Also put through [WAVE](https://wave.webaim.org/) to test colour contrast through out.

# Performance Testing

# Bugs Found 

No bugs found. 

During development the following issues occured but were fixed prior to deployment:


# Deployment 

This project has been publish on [GitHub Pages](https://github.com/SamanthaBooth81/High-Low-Game). 

To deploy my site to GitHub Pages I completed the following steps:    

- Ensured all code had been committed and pushed into my GitHub Repository. 

- clicked on **Settings**, found at the end of the navigation bar within the Repository.

- Once in Settings, scrolled down and clicked on **Pages** located near the bottom of the left navigation bar.

- Saved the **Source** as **Root** to ensure the webpage will be built from the main branch.

- Once the source had been saved, GitHub Pages generated a link to my live site. 

# Credit
## Content 

- Homepage image was downloaded from [Unsplash](https://unsplash.com/photos/d_QnWli2BA8).


# Acknowledgments
Thank you to all who encouraged and supported me as I created my first game, espcially to my mentor for his guidance and patience and Student Support at The Code Institute for helping me fix a problematic bug.
