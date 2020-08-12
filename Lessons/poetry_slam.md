# Poetry Slam

## Description
In this project we will write a Python program to print out poetry backwards, randomly, and any way you can rearrange!
By reading a poem in news ways we can discover new meanings or invite new interpretations.

Credit to Mark D. LeBlanc for their project posted on EngageCSEdu

## Learning Outcomes
By completing this project, you should be able to…

1. Implement functions
1. apply file input and output
1. Practice storing items in lists and reading from them
1. Implement loops
1. String manipulation and formatting
1. Apply the random module to your programs
1. Make connections to fields outside of CS

## Requirements

1. You will store your poem in a .txt file 

1. Your code should implements the get_file_lines() function. This function takes in a filename as a string and returns a list of strings containing the lines of the file.

1. Your code should implement the lines_printed_backwards() function. This function takes in a list of strings containing
the lines of your poem as arguments and will print the poem lines out in reverse with the line numbers reversed. For example, if you poem is Invitation by Shel Silverstein:

If you are a dreamer, come in,\
If you are a dreamer, a wisher, a liar,\
A hope-er, a pray-er, a magic bean buyer…\
If you’re a pretender, come sit by my fire\
For we have some flax-golden tales to spin.\
Come in!\
Come in!

then your function will print:

7 Come in!\
6 Come in!\
5 For we have some flax-golden tales to spin.\
4 If you’re a pretender, come sit by my fire\
3 A hope-er, a pray-er, a magic bean buyer…\
2 If you are a dreamer, a wisher, a liar,\
1 If you are a dreamer, come in,

1. Your code should implement the lines_printed_random() function which will randomly select lines from a list of strings and
print them out in random order. Repeats are okay and the number of lines printed should be equal to the original number of lines
in the poem (line numbers don't need to be printed). Hint: try using a loop and randint()

1. Your code should implement a function of your choice that rearranges the poem in a unique way, be creative! Make sure that you carefully comment your custom function so it's clear what it does.

1. Your final submitted code should use the four functions your wrote and print out the poem contained in your text file backwards, random, and custom. 

1. Your submitted code should be in a repo on Github and should have a minimum of 5 commits, you will need to submit the link to your repo on gradescope in order to receive a grade

1. Feel free to use any poem of your choice!

1. The class session after this assignment is due we will have an optional poetry reading in class!

### Stretch Requirements/Challenges (Optional)
1. Modify your program to have a menu that the user can select from rather than printing all the options at once
1. Modify your program to read the poem from user input
1. Modify your program to randomly rearrange the words on each line

## Rubric
This project will be graded using the [Poetry Slam Rubric](https://docs.google.com/document/d/1pXQeuD7R4ZRCjPQLvnVSdyCiAwOz5qDPXTxAgNS_2rM/copy)


## Resources
Additional resources that will help with this project, or that can be used as reference

- [Shel Silverstein Poems](http://thewhynot100.blogspot.com/2014/05/46-short-and-sweet-shel-silverstein.html)
- [Harlem Renaissance Poems](https://education.cu-portland.edu/blog/classroom-resources/harlem-renaissance-poets-for-your-reading-list/)