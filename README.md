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
is_prime :: Integer->Bool
check n = [x | x <- [1..n], mod n x == 0]
is_prime n = check n == [1, n]
2. Please write a function that calculate nth number of fibonacci sequence. For example,
```
> fibo 1
0
> fibo 5
3
```
Answer:
fibo::Int->Int
fibo 0 = 0
fibo 1 = 0
fibo 2 = 1
fibo n = fibo (n-1) + fibo (n-2)


## Questions
Q1: What is GraphQL and how it is different from REST API?

A1: GraphQL is a query language to access data from various API query system.REST API will need to determine the structure of the data first.This is one of the main problems of the REST API.So GraphQL is another way to create a better API.


Q2: Please explain how javascript benefits from cross-platform development

A2: Javascript can use a same code that can run on several platform.

Q3: What do you expect to get from during an internship at TakeMeTour?

A3: I would like to improve myself such as knowledge,teamwork,expirience.

## Submitting

Please fork this repo and submit your repository at panj@takemetour.com along with your contact information.

Note: These challenges must be done by yourself. There is no benefit for both sides if the answer do not reflect your true skill.
