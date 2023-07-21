# Turtle-Crossing-Game
![turtle_crossing](https://github.com/buczyniak/Turtle-Crossing-Game/assets/78871310/b1455fc1-07a0-4eb7-9399-5142c57204a1)

## Introduction to the Turtle Crossing Game
Turtle Crossing Game is an exciting arcade-style game where players control a cute turtle attempting to 
safely cross a busy street filled with moving cars. The goal is to guide the turtle to the other side while 
avoiding collisions with cars. As the game progresses, the turtle faces increasing challenges, such as 
faster cars and more traffic. Players must strategize and time their movements to achieve high levels and 
scores, making it an engaging and fun gaming experience.

The Turtle Crossing Game demonstrates the principles of Object-Oriented Programming (OOP), encapsulating 
game elements into classes with attributes and methods. The game provides an enjoyable challenge to players, 
requiring quick reflexes and strategic thinking to guide the turtle safely to the other side. Players strive 
to achieve higher levels and scores while navigating through traffic, making it a captivating and entertaining 
gaming experience.

The Turtle Crossing Game was created while taking a [Udemy course](https://www.udemy.com/course/100-days-of-code/).

## Explanation of the Code
1. main.py
  The main.py script sets up the game screen using the Turtle library and creates instances of the Player,
  CarManager, and Scoreboard classes. It listens for the "Up" key to move the player turtle upwards. The game
  loop (while game_is_on) updates the screen, creates and moves cars, and checks for collisions with cars and
  successful crossing of the turtle. The game ends when the turtle collides with a car or successfully crosses
  the street.

3. car_manager.py
  The car_manager.py file contains the CarManager class, responsible for managing the cars in the game. It
  creates and moves cars across the screen at random intervals and speeds. The cars have different colors, and
  their speed increases as the game progresses.

5. player.py
  The player.py file contains the Player class, which represents the turtle controlled by the player. The turtle
  can move up and down on the screen. It starts at the bottom of the screen and needs to reach the top to successfully
  cross the street. The is_at_finish_line() method checks if the turtle has reached the finish line.

7. scoreboard.py
  The scoreboard.py file contains the Scoreboard class, responsible for displaying the current level and handling
  score updates. It shows the level at the top-left corner of the screen. As the turtle successfully crosses the
  street, the level increases, providing players with a sense of progression.
