# Welcome to Agile Lab!

This is our technical test. Once you are done, you can either upload the answers to your own repository and share us the link, or you can zip your answers up and send it directly to us via email!

Enjoy!

## 1. Anagram Tester

An anagram is created by re-arranging the letters of a word. For example, the word `LISTEN` is an anagram of `SILENT`.
You can find the definition in [Wikipedia](https://en.wikipedia.org/wiki/Anagram).
Below is a skeleton defenition of a method for testing if two words make an anagram. Your task is to implement this
method, using PHP. It should take in two strings and return `true` if the two words make an anagram, or `false` if it's not.

```php
function anagram($first_word, $second_word) {
  // Add your implementation here
}
```

**Rules:**
 - You don't need to care about upper- and lowercase letters. That is, `A` and `a` can be considered the same for the purposes of this test.
 - You only need to care about single words. The method does not need to handle sentences.
 
## 2. Rewrite Pow

The pow() function in PHP is used to calculate a base raised to the power of exponent. 
It is a generic function which can be used with number raised to any value.
It takes two parameters which are the base and exponent and returns the desired answer.

Please rewrite your own `POW` method using multiplier operator `*`

```php
function my_pow($base, $exponent) {
  // Add your implementation here
}
```

## 3. Knowledge base
### 3.1 SQL Injections
What are SQL Injections, how can we prevent them and what are the best practices in PHP to prevent them?

### 3.2 N+1 Query
What is N+1 Query? and How we can improve it?

**Tips:**
- You are free to make **ANY** assumptions of framework/tools you use, write down your assumptions.

### 3.3 `===` vs `==`
How are they different, when to use `===` and when to use `==`

### 3.4 Server Variable
How you get server variable in PHP?

### 3.5 Test Unit / Unit Testing
What is Unit testing and how would you do it? What’s your opinion of unit testing?
 
## 4. Bug Fixing

When client or users reported an issue to you, describe what you do next.
How do you go about trouble shooting the issue? Depending on what you find, what will your next step be? When do you
consider the issue fixed or resolved?

**Tips:**
- You are free to make **ANY** assumptions, write down your assumptions.

## 5. Taking over an old project

You have recently been assigned to an old project, the previous developer had already left and you are tasked to take over the project and implement new features.
However you are facing some problems, the new feature that you are implementating doesn't seem to go well with the existing features.
The more you code, the more edge case you encounter.

Describe, in as much detail as you like, how you would handle this situation.

**Tips:**
- You are free to make **ANY** assumptions, write down your assumptions.
