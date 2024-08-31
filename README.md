# Finite-state-lab
Understanding state to build games

## Introduction
This project is a choose your own adventure game using Twine, an open-source tool for making interactive stories. 

## Technical Framework
This project was developed on Twine. This was the only framework used to make this project.

## Installation & Running the Project 
To run this project:
1. Get Twine
- Twine can be accessed in your browser using this link: https://twinery.org/2
2. Download story
  - Download the project file on your local machine: https://github.com/angelesmarin/Finite-state-lab/blob/main/Story.twee
3. Import story
- From the menu bar, go to Library, then import. Import the downloaded story.twee file.
4. Open & play story
  - Double click the story to open
  - In the menu bar, go to build, then play to play the game

 ## How Nodes are Stored 
 Each node represents a passage, which serves as a page, or section with text from which decisions are made. Each node/ passage has a title, a message, and a link to a choice that connects a passage to a different passage, which is how the story is navigated. 

 ## Mechanism for Switching Between Nodes
 [[text choice->node choice]] -This format is used by twine to link nodes together. 'text choice' is what the player sees; it is the choice they can click on in the game. 'node choice' is what directs the player to the corresponding node when they click their choice. 

 ## Reflection 
 Writing a story is hard. I am not a very creative person so I struggled with comming up with a 'choose your own adventure' concept. I have never really played video games, so it was intresting to see how a game like this can be represnted by so many different data structures. It was really intresting to me to learn about how involved data structures and algorithms are in game development are, like tables, graphs, and trees. 

