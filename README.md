### TakeMeTour Internship Program 2017

Hi all applicants! Welcome to TakeMeTour Internship Program 2017. Being and intern at TakeMeTour is challenging so we have challenges for you! These challenges are designed to assess your learning skill, which is the fundamental and most important skill of great software developer. So I do not expect you to have full or any knowledge about the topic beforehand but it's your job to try to learn and answer those challenges.

## Haskell

Haskell is a functional programming language. The fundamental concept is totally different to the traditional (imparative) language.
1. Please write a function that check if the input number is prime number. For example,
```
> is_prime 5
True
> is_prime 4
False
```
Answer:
```
-- insert your answer here
isPrime Integer -> Integer -> Boolean
isPrime x 1 = True
isPrime x y
   | x `mod` y == 0 = False
   | otherwise = isPrime x y-1
 
is_prime :: Integer -> Boolean
is_prime 3 = True
is_prime 2 = True
is_prime n
   | n < 2      = False
   | otherwise  = isPrime n n-1
```
2. Please write a function that calculate nth number of fibonacci sequence. For example,
```
> fibo 1
0
> fibo 5
3
```
Answer:
```
-- insert your answer here
Fibonacci Integer->[Integer]->Integer->Integer 
Fibonacci n (x:y) z
   |y==z = n
   |y>z = -1
   |otherwise = Fibonacci n+1 [y,x+y] z 

Fibo Int->Int
Fibo z = Fibonacci 0 [1,1] z

```

## Questions
Q1: What is GraphQL and how it is different from REST API?

A1: GraphQL is query language for your APIs.It was create by Facebook. 
It will sent to a server for executing queries then return back to cilent by using a type system you define for your data.
GraphQL isn't tied to any specific database or storage engine. 
    REST API is an architectural concept for network for network-based software.
Rest API need to use HTTP verbs standard.
But GraphQL don't use HTTP standrad.Rest API have many standard of Scheama and Type such as JSON Screama or OpenAPI.
But GraphQL have type System so it have only one standard.
GrapQL is easy to use when you have to manage complex field and data.
Rest API is easy when data isn't complex. Rest is more easy than GraphQL to create API. 



Q2: Please explain how javascript benefits from cross-platform development

A2: JavaScipt is computer language for develop internet.
Advantage of cross-platform development is you can write one application and run in several platforms.
Instread of having many platform with different language.JavaScipt is open programming language ,
so it's freely.JavaScript are fast enough for most applications.JavaScript is widely used ,
so there are many document and support.

Q3: What do you expect to get from during an internship at TakeMeTour?

A3: I expect to get experince of working and get more knowledge from others.
I want to do some new thing and learn how to work at Company. Finally, I wish I will get new friends at TakeMeTour.

## Submitting

Contract info:Nithirun Numnonda mobile:0831411163 email:nithirun1995@gmail.com
