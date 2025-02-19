# Tasks

## Task 1:

### Description

Digital personal assistants help people drive cars, plan their day, and buy something online. In a sense, they are simplified versions of artificial intelligence with whom you can talk.

In this project, you will develop, step by step, a simple bot that will help you study programming.

### Objectives

For the first stage, you will write a bot that displays a greeting, its name, and the year it was created. First impressions count!

Your program should print the following lines:
   

```
Hello! My name is {botName}.
I was created in {birthYear}.
```



Instead of `{botName}`, print any name you choose and replace `{birthYear}` with the current year (four digits). You don't need to take any input at this stage.

## Task 2:

### Description

The greeting part is great, but chatbots are also supposed to interact with a user. It's time to implement this functionality.

### Objectives

In this stage, you will introduce yourself to the bot so that it can greet you by your name.

Your program should print the following lines:

```
Hello! My name is Aid.
I was created in 2023.
Please, remind me your name.
What a great name you have, {yourName}!
```

## Task 3

### Description

Keep improving your bot by developing new skills for it. We suggest a simple guessing game that will predict the age of a user.

It's based on a simple math trick. First, take a look at this formula:

```
age = (remainder3 * 70 + remainder5 * 21 + remainder7 * 15) % 105
```

The numbers `remainder3`, `remainder5`, and `remainder7` are the remainders of the division of `age` by 3, 5, and 7 respectively.

It turns out that for each number ranging from _0_ to _104,_ the calculation will result in the number itself. This perfectly fits the ordinary age range, doesn't it? Ask the user for the remainders and use them to guess the age!

### Objectives

In this stage, you will introduce yourself to the bot. It will greet you by your name and then try to guess your age using arithmetic operations.

Your program should print the following lines:

```
Hello! My name is Aid.
I was created in 2023.
Please, remind me your name.
What a great name you have, Max!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
Your age is {yourAge}; that's a good time to start programming!
```

Read three numbers from the standard input. Assume that all the numbers will be given on separate lines.

Instead of `{yourAge}`, the bot will print the age determined according to the special formula discussed above.

## Task 4

### Description

Now you will teach your bot to count. It's going to become an expert in numbers!

### Objective

In this stage, you will program the bot to count from 0 to any positive number users enter.

## Task 5

### Description

At the final stage, you will improve your simple bot so that it can give you a test and check your answers. The test should be a multiple-choice quiz about programming with any number of options. Your bot has to repeat the test until you answer correctly and congratulate you upon completion.

### Objective

Your bot can ask anything you want, but there are two rules for your output:

* the line with the test should end with the question mark character;
* an option starts with a digit followed by the dot (`1.`, `2.`, `3.`, `4.`)

If a user enters an incorrect answer, the bot may print a message:

```
Please, try again.
```

The program should stop on the correct answer and print `Congratulations, have a nice day!` at the end.
