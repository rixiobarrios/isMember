[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)


---
Title: isMember Coding Challenge <br>
Type: Homework <br>
Duration: "0:45"<br>
Creator: Carlos Godoy <br>
Competencies: Arrays, Loops, Breaking down a problem into smaller steps<br>
Prerequisites: JavaScript Fundamentals<br>
Coding Challenge from: Hackerrank

---


# Is this word a member word?

You are given an array of words and a string query. You must return true or false depending on whether the array of words contains the query or not.

A query may contain the wildcard character "*" which can match with any character. If you're familiar with card games, think of the "*" as the Joker card which is also a wildcard and can represent any card in the deck.

```
Examples

words = ["bing", "bang", "boom"];

 

isMember(words, "bing") // true   (because 'bing' exists in the list of words)
isMember(words, "hello") // false  (because 'hello' does NOT exists in the list of words)


isMember(words, "ba*g") // true  (because the "*" matches the "n" in bang)
isMember(words, "**") // false (no two letter words)

 

isMember(words, "*oom") // Is this true or false?
```


### Code

Write a function `isMember` that takes an array of words and a string as arguments

```
isMember(words, bam) //should be false
isMember(words, **ng) //should be true
isMember(words, b**m) //should be true
isMember(words, *oo*) //should be true
```


### Was this TOO EASY?
Make an account at <a href="https://hackerrank.com">Hackerrank</a> and sign up for their 30 Days of Code challenge to practice new coding challenges every day!


