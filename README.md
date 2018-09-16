# Tut-01

## WHAT WE'RE DOING

- finding a partner
- making sure you can get on INS
- creating 2 algorithms with your partner
- submitting your 2 algorithms
- getting your first assignment

---

## FINDING A PARTNER

Follow this algorithm:

```
If there is someone to your right
  point at that person
Else if there is someone to your left
  point at that person
Else
  stick your hand up in the air

If you are pointing at someone who is pointing at you
  partner with that person and ignore the rest of these instructions
Else if your hand is not up and if there is someone to your left
    point at that person

If you are pointing at someone who is pointing at you
  partner with that person and ignore the rest of these instructions
Else
  stick your hand up in the air

Do the following starting with the front row until there are 1 or 0 people with their hands up
  partner with the person closest behind you with their hand up
```

Sit down so that you are seated next to your partner - you decide how to do this because frankly I'm exhausted from the algorithm.

Log in to your computer.

## MAKING SURE YOU CAN GET ON INS

We did this on Thursday, but in case you weren't there, please log into INS.

If you don't know how to do this, ask your partner.

If both you and your partner don't know how to do this, ask another pair.

If you have any issues logging in, call your instructor over.

## CREATING 2 ALGORITHMS

Remember from lecture on Monday that we talked about the process used to program:

1. Understand the problem
1. Develop an algorithm
1. Test the algorithm with simple inputs
1. Translate the algorithm into Java
1. Compile and test (repeat until "done")

We'll be doing parts 1 through 3 in this lab.

We'll do one problem together, and then you can work on the next two with your partner.

**For each algorithm, note any assumptions you have made.**

### Demo: Sandwich Calorie Calculator

We've been asked to create a program that calculates the total calories in a sandwich.

Suppose we have the following caloric values:

- one slice of bread = 63
- one slice of cheese = 106
- one Tablespoon of mayonnaise = 49
- one pickle = 25
- one slice of mystery meat = 43

Design an algorithm to ask a user for a sandwich composition, calculate the total calories in that sandwich, and then report the result.

### Algorithm 1: Better pairing

Save this algorithm in a file called `algo-1.txt`.

We followed an algorithm at the start of class to pair up. It wasn't the greatest. For example, it doesn't work that well if you have rows with more than 5 people in it...do you see why?

Create an algorithm to create pairs that works for rows of any size > 0.

Don't forget to give your algorithm a test drive.

### Algorithm 2: House painting

_(modified R1.15, p. 25 in the text)_

Save this algorithm in a file called `algo-2.txt`.

We are asked by a house painting company to create a program which estimates the paintable surface area of a house. They will use this to estimate how much paint they will need for a given job.

Decide what inputs are necessary.

You will need to make some assumptions to make this a manageable task; write these assumptions down with your solution.

Don't forget to give your algorithm a test drive.

## SUBMITTING YOUR 2 ALGORITHMS

Put your algorithm file into a directory named `tut-01` and submit that directory via the `submit` command.

## GETTING YOUR FIRST ASSIGNMENT

Going forward, you will always find the starting code for assignments in `/users/library/csis/comp1501/assignments`.

Copy the `1.asg` directory there to your home directory. If you can't remember what command to use, there's always the https://bit.ly/mru-1501-linux-ref

Instructions for the assignment are here: https://github.com/MRU-CSIS-1501/201804.asg.01.documentation
