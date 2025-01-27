# Software Engineering, CSCI-UA 474
Taught by Amos Bloomberg in Spring 2024
<details>
<summary>Course Description:</summary>  
  CSCI-UA 474 Software Engineering  
  
An intense hands-on study of practical techniques and methods of software engineering. Topics include advanced object-oriented design, design patterns, refactoring, code optimization, universal modeling language, threading, user interface design, enterprise application development, and development tools. All topics are integrated and applied during the semester-long group project. The aim of the project is to prepare students for dynamics in a real workplace. Members of the group meet on a regular basis to discuss the project and to assign individual tasks. Students are judged primarily on the final project presentations.  
<br>

Teck Stack: Git, Github, Docker, Python, Pandas, Figma
</details>

## [Project 1: Specification (Assignment Manager)](https://github.com/software-students-spring2024/1-specification-exercise-team-temp-name)

## [Project 2: Web App (Assignment Manager | Python/MongoDB )](https://github.com/software-students-spring2024/2-web-app-exercise-wae_team)

<details>
<summary>Overview:</summary>    
<br>

[Specification](https://github.com/software-students-spring2024/1-specification-exercise-team-temp-name)    
<br>

A webapp allowing users to keep track of classes and assignments for school. This app allows users to add class pages with notes, assginemnts, and the grading weights of different assignments and test allowing for them to keep track of their grades in any given class as well as any upcoming due dates with a calendar view. This app also has a calendar page where the user can look to see any upcoming assignments, and any notes that might go along with the assignment posting. When an assignment is complete the user can input the number of points the assignment was worth along with their and their score and their current grade will automatically be updated based off of the catgorical weights in the class. 
</details>

## [Project 3: Python Package (Probability Python Package | Python/PyPl/pip)](https://github.com/software-students-spring2024/3-python-package-exercise-ppe)

<details>
<summary>Overview:</summary>    
<br>

This is a Python package available on PyPl to be downloaded using pip. This package include six different probablity simulations:
```py
coin_flip(num_coins=1)
```
 This function returns the results of (num_coins) coin flips. Defaulting to one coin with no user input.
 ```py
dice_roll(num_dice=1, sides=6)
```
This function returns the results of (num_dice), (sides) sided dice rolls. Defaulting to one dice with six sides.
```py
draw_cards(num_hands=1, num_cards=1)
```
This function draws (num_hands) hands of (num_cards) cards with no repeats up to 52 cards total. Defaulting to one hand with one card.
```py
generate_powerball()
```
This function generates a Powerball number according to the powerball guidelines (5 numbers 1-69, 1 number 1-26). 
```py
draw_from_bag(itemTypes=["red","blue","green"], itemNums=[3,3,3], drawNum=1)
```
This function allows a user perform drawings of any number of different objects from a bag with costum quantities. Defaults to one drawing of "red","blue", or "green" with equal probability. 
```py
prob_simulator(outcomes=["yes", "no"], probabilities=[0.5, 0.5], num_trials=1)
```
This function allows a user to create their own probability scenario with custom outcomes and probabilities which are then scaled to total 1 regardless of the values of the input. Defaulting to a 50/50 probability of win or lose with no user input. 

</details>

## [Project 4: Containers (Color Finder | Python/Docker/MongoDB )](https://github.com/software-students-spring2024/4-containerized-app-exercise-cae)

<details>
<summary>Overview:</summary>    
<br>
This app takes an image from the users camera and returns the detected color as its  RBG values, HEX code and color name.
<br>
<br>
This process is done as follows.

1. This app takes an image from the user's available camera.
2. The image is then sent to the database running in another Docker container within the build.
3. The machine learning client receives the message from the web app, and will grab the image data from the database.
4. The machine learning client then analyzes the image's main color palette, and will output its RBG, HEX and color name.
5. The output color data will be sent back to the database.
6. The web app will receive the feedback message from the machine learning client, and will grab the color data from the database.
7. The grabbed color data will be used in rendering web page template, and thus making the web page display the final result to the user.
 
</details>

## [Project 5: Final (World Builder | Python/Docker)](https://github.com/software-students-spring2024/5-final-project-spring-2024-se-final)

<details>
<summary>Overview:</summary>    
<br>

This project is a world building manager web application which allows for the following functions:
- User can create project pages for their world building in the app with a title, description, characters, and locations.
- User can add new characters & locations with customized details and notes to a specific project.
- User can edit any details they want by accessing the project, character, or location details page and then save the changes.
- User can delete any project, character, or location they would like to discard.

</details>
