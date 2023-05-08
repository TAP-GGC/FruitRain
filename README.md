# FruitRain

## Project Title: Fruit Rain

## Description:
Fruit Rain is an educational game designed to teach students of all ages the fundamentals of Java programming. Players will be asked a series of questions, and answers can be found on the fruit falling from the top of the screen. Players answer these questions by tapping the fruit that matches the one in the game that they believe has the correct answer. This controller setup is achieved using a Makey-Makey controller; an apple, orange, banana, and lime; and alligator connectors. This approach to learning has been effective at increasing students' enthusiasm towards programming.

This project was developed by members of the Technology Ambassadors Program, a program at GGC whose goal is to encourage others to seek careers in technology and show them that programming isn't as scary as it may seem at first. https://www.ggc.edu/academics/school-of-science-and-technology/research-internships-service-learning/technology-ambassador-program

A short video demo of the project can be found here: *insert link to media video*

## Team:
The Team behind this project consists of-
Justin Portillo
Dionys  Del Rosario
Chloe Vedrine

*link to team photo*

The class was instructed by-
Dr. Xin Xu
Dr. Wei Jin

## Publications
CREATE Symposium Spring 2023 Presentation
STARS Poster Spring 2023 Presentation

## Outreach Activities
Atlanta Science Festival Spring 2023
TAP Expo Spring 2023
2 Workshops - ITEC 1001, ITEC 2110

## Technology

The program was developed using Java, with Processing as our IDE (Integrated Development Environment) https://processing.org/ . Inputs are handeled using a Makey Makey controller, a variety of fruit, and a Makey Makey controller https://makeymakey.com/ .
*Insert picture of controller*

## Project Setup/Installation

Download all of the files from GitHub as a zip file.

You will need to open the FruitRain.pde file and go to around line 448 and
paste in the file location of QuizQuestions.csv. You can do this by locating them in
your file explorer, right clicking the section that shows all of the folder names,
and clicking "Copy address". Then paste the addresses in place of the pre-written
addresses, add an extra "\" to each one present in the new address, followed by two
backslashes and the file name.

E.g.: C:\\Users\\username\\Downloads\\FruitRain-FolderFruitRain\\QuizQuestions.csv

Confirm that the file paths work as intended; if there is something wrong, an error
should occur upon attempting to run the program.

While you have this file open, you will need to download the Sound library;
to do so, click on Sketch, then hover over Import Library, then click Add Library
(depending on your version of Processing it may be a different option).
Search for the Sound Library and download. If no errors occur when attempting to
play the music, then you've done this step correctly. You will also need to download the GifAnimation library.

Hook up the Makey-Makey controller to your PC and connect an apple, orange,
banana, and lime to the controller's up, down, left, and right dpad areas respectively
with alligator connectors. These dpad directions are automatically mapped to the corresponding
arrow keys on your keyboard, so no further configuration is required. If fruit and/or makey-makey controllers are not available, we recommend colored stickers on the arrow keys instead, as there is otherwise no indication of what to press.

Connect the wrist-strap to the ground connectors on the controller.

## Usage

Have the player put on the wrist-strap so that they can play the game. The electricity sent through the ground wire is very weak, so there shouldn't be any risk of electrocution. Consult any instructional documents that came with the controller if you have any concerns.

Players will tap the fruit that corresponds with their guess to a provided question.
We suggest printing out a word document briefly explaining the following java concepts:
variables, strings (including concatenation), and conditionals (if, else, and
while loops).

Avoid holding onto the fruit, doing so will cause the directional input to be read several times. Simply tap the fruit very briefly.

## Additional Notes:

The variables2.csv file features questions relating to a wider variety of arithmetic and assignment operators.
To change the quizzes you wish to use, change the file name(s) listed in the keyPressed() method on line 294.
We would also recommend changing lines 189, 191, 193, and/or 195 accordingly.

While this game was originally developed to teach the fundamentals of programming, because we used csv files to store the quizzes, it can easily be re-purposed to teach any other subject, such as Mathematics, Chemistry, History, Trivia, etc.

If you want to create your own quiz for the game (be it to teach programming or any other subject), create a csv file and follow the format of the other files.
We recommend doing this in excel or google sheets because the rows are more clear that way. The correct answer
choice is notated in what would be their arraylist index, as in you start counting from 0 rather than 1.
i.e. if the correct answer is the second choice, put a "1" in the last used cell of that row.

When building the quiz, you have the choice of four answers or two. For four answers, set the third cell of the row to 1. For two answers, set it to 2.
The second column is used for question IDs, the program itself never uses these values, they're simply meant for your own organization.

The file names in lines 189-195 must match the quizzes you intend your players to try to complete.

**Notes: Workshop does not have started code 
