# Simple-Chatty-Bot

**About:**
Here, at the beginning of your programmer’s path, you will need a console bot that will guide you through the basics of software development. During this journey you will also play some word and number games that you are going to implement by yourself. Pack up and hit the road, my friend!

**Result:**
As you move through the project, you’ll install Java on your machine and learn to work in a professional development environment. You’ll get to know the basic syntax of Java and write a simple program using variables, conditions, loops, and methods.

# Work on project. Stage 1/4: Hello! What’s your name?

Description
Digital personal assistants help people to drive cars, plan their day, buy something online. In a sense, they are simplified versions of artificial intelligence with whom you can talk.

In this project, you will develop step by step a simple bot which will help you to study programming.

For the first stage, you will write a bot who displays a greeting, its name and the date of its creation.

Your program must print the following lines:

Hello! My name is {botName}.
I was created in {birthYear}.
Instead of {botName} print any name you choose and replace {birthYear} with the current year (four digits), ex:

Hello! My name is Aid.
I was created in 2018.
You can change the text if you need but print exactly two lines.

Next, we will use Aid and 2018 as your assistant's name and its birth year, but you can change it if you want.

# What you'll do in this stage 2/4: How old are you?

Description
At this stage, you will introduce yourself to the bot. He will greet you by your name and then try to guess your age using arithmetic operations.

Your program must print the following lines:

Hello! My name is Aid.
I was created in 2018.
Please, remind me your name.
What a great name you have, {yourName}!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
Your age is {yourAge}; that's a good time to start programming!
You may change the name and the creation year of your bot if you want.

Instead of {yourName}, the bot must print your name entered from the standard input. Instead of {yourAge}, the bot must determine your age according to the following formula:

age = (remainder3 * 70 + remainder5 * 21 + remainder7 * 15) % 105
Where remainder3, remainder5 and remainder7 is three numbers you input to the program.

Here is an example of a dialogue with the bot. Input lines are started with ">" symbol. You do not need to read this symbol.

Hello! My name is Aid.
I was created in 2018.
Please, remind me your name.
> Max
What a great name you have, Max!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
> 1 2 1
Your age is 22; that's a good time to start programming!
Use the provided template to simplify your work. You can change the text, but not the number of printed lines.

# What you'll do in this stage 3/4: Let’s count!

Description
At this stage, you will program the bot to count from 0 to any positive number you entered.

Here is an example of a dialogue with the new version of the bot. Input lines are started with ">" symbol.

Hello! My name is Aid.
I was created in 2018.
Please, remind me your name.
> Max
What a great name you have, Max!
Let me guess your age.
Say me remainders of dividing your age by 3, 5 and 7.
> 1 2 1
Your age is 22; that's a good time to start programming!
Now I will prove to you that I can count to any number you want.
> 5
0!
1!
2!
3!
4!
5!
Completed, have a nice day!
Note, each number starts with a new line, and after a number, the bot should print the exclamation mark. Do not output any extra characters in these lines with numbers.

Use the provided template to simplify your work. You can change the text if you want, but be especially careful with counting numbers.

# Work on project. Stage 4/4: The student and the teacher

Description
At this stage, you will improve your simple bot so that it can give you a test and check your answers. The test should be about programming. Your bot has to continue to ask the test until you answer correctly.

Your bot can ask anything you want, but there are two rules for your output:

the line with the test should end with the question mark character;
an option starts with a digit followed by the dot (1., 2., 3., 4.)
If a user enters an incorrect answer, the bot may print a message:

Please, try again.
Here is an example of a dialogue with the new version of the bot. Input lines are started with ">" symbol.

Hello! My name is Aid.
I was created in 2018.
Please, remind me your name.
> Max
What a great name you have, Max!
Let me guess your age.
Say me remainders of dividing your age by 3, 5 and 7.
> 1 2 1
Your age is 22: that's a good time to start programming!
Now I will prove to you that I can count to any number you want.
> 3
0!
1!
2!
3!
Let's test your programming knowledge.
Why do we use methods?
1. To repeat a statement multiple times.
2. To decompose a program into several small subroutines.
3. To determine the execution time of a program.
4. To interrupt the execution of a program.
> 4
Please, try again.
> 2
Congratulations, have a nice day!
The program must end with the Congratulations, have a nice day! message.

Use the provided template to simplify your work. You can change the text if you want. Please note that we use methods to make it easy to understand the program and add to or edit later.
