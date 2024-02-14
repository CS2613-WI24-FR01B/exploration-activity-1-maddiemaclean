# Library Overview

## Question 1. Which Package did you Select
The library I choice was Faker.js for JavaScript

## Question 2.What is the package/library
### 2a. What purpose does it serve?
Faker.js is a library that generates data such as names, phone numbers, words, addresses, account numbers, hexadecimal numbers and other common data often used in programming. Faker.js also includes more niche data such as vehicle number, airplane model and cat breed. This makes testing your code much easier as you don’t need to create all of the fake data by yourself. Let’s say for example, you are making a program that sorts an array of words alphabetically. Usually, you would need to make a couple different arrays and fill them with a bunch of different words. This not only takes time, but also allows bias. For example, you could miss a case where there is a flaw in your code. With the randomness Faker.js provides, you can find errors in your code and create a more realistic testing environment. Additionally, you can use Faker.js to make quick working demos rather than spending hours creating your own data. [1][2]

### 2b. How do you use it
Faker has a bunch of functions which create random data. When you need some common data to test your code, you can use one of the many functions that Faker.js provides to create it. How Faker works is that there’s different randomizers which generate different data, each one is sorted into a category. Certain useful categories being Finance, Person, Word and Location. [2]

## Question 3. What are the functionalities of the package/library?
The purpose of Faker.js is to generate fake but viable data to use while testing or developing code. For example let’s make a person, each person has a fullName, gender and job title. Rather than having to make 20 people with different names, genders and jobs, you can do something like
> let person1= new person(faker.person.fullname(),faker.person.gender(),faker.person.jobTitle());
> 
> let person2= new person(faker.person.fullname(),faker.person.gender(),faker.person.jobTitle());
> 
> let person3= new person(faker.person.fullname(),faker.person.gender(),faker.person.jobTitle());

Now you can use this data to test your code. For this example, let’s imagine you just print out the people. This would be your output [3]

> Dr. Victor Anderson, Cis male, Future Configuration Facilitator
> 
> Marty Pollich, Intersex, Customer Identity Facilitator
> 
> Leigh Stoltenberg, Demi-boy, Principal Web Director

## Question 4. When was it created?
Faker was created in 2004 and first implemented into Perl and was later ported into many languages including JavaScript. [4]

## Question 5. Why did you select this package/library?
While exploring which package or library I wanted to use, I was instantly drawn to Faker.js. Creating fake data for testing code has always been something I've dreaded doing, and before Faker.js, there was no way to generate data excluding using Math.random() for certain numbers. So when I found out there was a way to create data, I knew I wanted to explore it further.

## Question 6. How did learning the package/library influence your learning of the language?
Faker helped me to reinforce concepts such as loops, iteration and data sctructures. It feels a lot easier to write a simple function in JS now then before I started the activity. It also forced me to think outside of the box and try to implement the ideas in my mind, rather than following lab instructions. 

## Question 7. How was your overall experience with the package/library?
I really enjoyed learning Faker.js. It was interesting to play around with all of the data it could generate. I didn’t encounter many issues with getting the library to work so it was fairly smooth to pick up and get working.
### 7a. When would you recommend this package/library to someone?
I would recommend this library to anyone who frequently tests code and needs a lot of test cases as it speeds up testing and makes it less of a headache.
### 7b. ould you continue using this package/library? Why or why not?
Yes! Since Faker.js makes testing smoother, I will start using it in my programs to save myself some time going foward.


# References 
> [1] https://fakerjs.dev/guide/
> 
> [2] https://fakerjs.dev/api/
> 
> [3] https://fakerjs.dev/api/person.html
> 
> [4] [https://fakerjs.dev/about/announcements/2022-01-14]https://fakerjs.dev/about/announcements/2022-01-14.html#:~:text=Faker%20was%20first%20implemented%20in%20Perl%20in%202004,including%20Ruby%2C%20Python%2C%20Java%2C%20Clojure%2C%20PHP%2C%20and%20C%23.
