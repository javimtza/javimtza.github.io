# Birthdhay Problem

A couple of weeks ago I was eating lunch with my family when I mentioned a fact I had seen a couple of days before: If there are 23 people in a room, there is a 50% probability that there is at least one shared birthday in the room. A burst of denial filled the room  .But rather than convince them that it was true, I decided to show them.

As we can see in Matt Stile's Blogpost, birthdays do not follow an even distribution, however for the purpose of this blog we will be assuming that the probability of any given birthday is equal (except of course february 29th which happens once every four years). meaning that the probability of a May 24th birthday is the same as a June 18th birthday.

### Theory
We will begin by stating some simple probability facts. Given our knowledge, we know that there is 1/365 ≈ 0.27% chance of any two people having the same birthday (1/366 if both were born on a leap year). By the rule of subtraction, we find that the probability of two people **not** sharing a birthday is 1 - (1/365) = 364/365 ≈ 99.73%.


| Number Of Dice To Roll Even | Multiplication | Probability |
|----------------|----------------|-------------|
| 1              | 1/2        | 1/2         |
| 2              | 1/2 * 1/2 = (1/2)<sup>2</sup>        | 1/4         |
| 3              | 1/2 * 1/2 * 1/2 = (1/2)<sup>3</sup>        | 1/8         |
|...             |...             |...          |
| n              | 1/2 * 1/2 * ... = (1/2)<sup>n</sup>             |1/2<sup>n</sup>          |
