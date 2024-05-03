# Kenya at 50!

## Objectives

- Building an interactive online quiz game platform focusing on Kenya with the aim of supporting the gaming culture which has been on an upward trajectory, whilst increasing awareness about the country. 

## Introduction

Kenya at 50! is a an online quiz game platform centered around Kenya. The platform has a number of quizzes focusing on various thematic areas such as History, Culture, Food, Geography and Music for a start. The end goal is to have a minimum of thirty thematic areas, with the number of questions under each category updated to twenty. These quizzes will be updated on a regular experience, to ensure returning visitors to the website have a similar experience to first time visitors. 

## Gameplay
Currently, the game functions as a single user game play. Each user accessing the platform will need unique login credentials, which they will key in in the Sign In area. Once the correct credentials have been keyed in, users will be redirected to the "Categories" page, where they'll choose a quiz depending on their area of interest. The quizzes are currently untimed, and each quiz has 10 questions. The score will be indicated after submitting the last question. Once a quiz is completed, the user will have the option of retrying the same quiz, or trying a different quiz. All the quizzes follow a similar standard of operation. 

## Codebase
## HTML
The structure of the gaming project has been built around HTML. The Home page `index.html` serves as the main page of the project, which redirects to other pages like "Categories" and "Play", through a combination of anchor elements and external html files. The html pages also have external css and javascript files linked to them through the link and script tags respectively, which serve the purpose of styling and making the website functionable. On top of the HTML boilerplate, tags which feature prominently in the codebase are section, img, link, a, button and input. Attributes which feature prominetly include class, id, href, src and alt. 

## CSS
The entire website has been styled using external CSS, with files linked to the respective HTML files they are stying using the link tags. CSS properties which feature prominently include background, margin, padding, font-size, font-weight, color, display, justify-content, align-items, transition-duration etc. The hover pseudo-class has also consistently being used, to ease in navigation. 

## JavaScript
The bulk of the functionality of the Website is done on JavaScript, which features prominently in the quiz sections. Here, we've made use of a number of methods e.g. .getElementById(), .createElement(), .appendChild() and .removeChild() to manipulate the DOM. Event listeners for click and submit events also play a role in the gameplay. Variables, functions, if statements and array methods support the functionality of the quizzes, while GET requests feature in the Sign In section, which will be used to communicate with the server. 

#### Targets for the next phase update

1. An increase in thematic areas from the current number (5) to thirty
2. An increase in the number of questions per quiz, from ten to twenty
3. Moving from single player to multi player
4. Creating a leaderboard to make the gaming competitive
