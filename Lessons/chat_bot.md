# Chat Bot

## Description
In this project, we will write a Python program to create simple [chat bot](https://www.cleverbot.com/) using conditionals, lists, and loops. Your chat bot will be focused on a specific topic so think about what kinds of questions you want your chat bot to answer!

## Learning Outcomes
By completing this project, you should be able to…

1. Implement more advanced functions
1. Use conditionals and boolean logic to control prompts and responses
1. Use lists to store and manipulate responses
1. Use loops to check for input
1. Use an imported function from a built-in module

## Set Up:
🚨  Before starting the assignment, watch [How to: Setup for a New Assignment](https://youtu.be/MCbDO8IpqZM). 

This tutorial walks your through how to set up a new repository, make commits, and push code to Github.
## Requirements

1. Create a function called get_bot_response() that will take in a string argument called user_response which is what the user will type in to your chat bot and will return a string with the chat bot's response. This function must:
    1. Use at least two lists to store at least three unique responses to different user inputs. For example, if you were building a mood bot and the user entered "happy" for how they were feeling your happy response list could store something like "I'm glad to hear that!", "Yay!", "That is awesome!".
    1. Use conditionals to decide which list to select from and randomly select one of the three responses using choice() from the random module. For example, if the user entered "sad" you would use choice to select one of the responses from the sad response list. 

1.Greet the user using print() statements and explain what the chat bot topic is and what kind of responses it expects.

1. Get user input using the input() function and pass that user input to the get_bot_response() function you will write

1. Print out the chat bot's response that is returned from the get_bot_response() function

1. Use a while() loop to keep running your chat bot until the user enters "done"

1. Your submitted code should be in a repo on Github and should have a minimum of 5 commits, you will need to submit the link to your repo on gradescope in order to receive a grade

1. Feel free to use any chat bot topic of your choice, it could be a mood bot or a bot that wants to talk about video games, be creative!

1. The class session after this assignment is due we will have a show and tell session where we can all try each other's chat bots out!

### Stretch Requirements/Challenges (Optional)
1. Modify your program to interpret even more complex responses and answers

## Rubric
This project will be graded using the [Chat Bot Rubric](https://docs.google.com/document/d/1RFZo2KHTOTVk-uL0LL93MUgSey-wPQjTvSRsxPyTivw/copy)
