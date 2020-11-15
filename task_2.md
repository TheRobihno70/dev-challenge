# Challenge Part 2: Quiz

In the following sections, you will find **5 questions**, of which you have to answer **only 3**. Please keep it short and clear. You can write your answers directly into this file.

For some questions, you will have to inspect websites or web applications, others are more an evaluation of frameworks. Feel free to answer whichever questions you like best (but choose three)! For each question, we also include a short statement on why we find each question relevant regarding the actual work you would be doing at the DBF.

## Q1: Advantages and Disadvantages of using React

**Question:** What are the advantages and disadvantages of using React to develop web applications? Name 2 each.
Advantages: One advantage of React is its testability, as it offers react's native tools for testing and debugging code. Another advantage is that react can be used with nearly any framework (i.e. angular.js) as it is only a view layer. This however could also be a disadvantage, as you still have to plug your code for events etc.
Disadvantages: As React is a relatively new technology, it has a more or less poor documentation. However it is growing everyday. Another disadvantage is that I personally think that the learning curve is quite steep the more advanced you are. 


**Response:** Write answer here.

_Why is it relevant:_ Almost all of our web development projects at the DBF, especially new ones, are based on the React framework. As such, it is important to understand why we started using the framework, and what could be the challenges in using it.

## Q2: Analyzing the Structure of an Application

**Question:** Look at the repository of the KlickerUZH frontend (<https://github.com/uzh-bf/klicker-react>). Can you figure out what the `Feedback` component located in `klicker-react/src/components/feedbacks/Feedback.tsx` is used for? Please include a short explanation of how you came up with your answer.

**Response:** Write answer here.

_Why is it relevant:_ As you will inevitably work with some of our existing projects over time (of which the KlickerUZH is one), it is important that you can understand the structure of an existing application, as well as use tools to help you with that task.

## Q3: Analyzing Websites

**Question:** Look at the course websites of the “Finance Weiterbildung” (e.g. <https://www.finance-weiterbildung.uzh.ch/de/programs/single-courses/angewandte-makrooekonomie.html>). This page uses an API to fetch data (e.g. ECTS-Credits etc.). What is the endpoint URL of this API?

**Response:** Write answer here.
The websites performs a GET request to following URL to get the data:
https://www.finance-weiterbildung.uzh.ch/static/website/api/public/index.php/de/courses/angewandte-makrooekonomie

_Why is it relevant:_ Almost all our apps and websites are built on a layered architecture, separating the view layer (frontend) from the data (data layer). The view layer is often implemented with a different technology, or even hosted separately, when compared to the data layer. It is important that you understand this concept and know how it can be applied.

## Q4: Continuous Deployment (CI/CD)

**Question:** The KlickerUZH is automatically deployed using CI/CD. What does CI/CD mean and what tasks can it perform? Name three examples of tasks you could perform in CI/CD to improve system stability, quality, or developer experience.

**Response:** Write answer here.

_Why is it relevant:_ CI/CD has many advantages, which is why we are using it wherever possible, be it with GitHub Actions or GitLab CI. It is important to be familiar with the topic, as it can greatly improve your efficiency.

## Q5: Programming Languages

**Question:** What has been your favorite programming language / framework so far? Why do you like it and how does it compare to other technologies? What was the hardest challenge you have faced with that specific technology?

**Response:** My favourite programming language so far has to be java, closely followed by python. I mainly chose java because it's the language I have most experience in. Python is really close as python was my first programming language and python is really intuitive. However, after I learned java, I got used to use semicolons and seperate blocks of code not only with intendations but also with parenthesis, which in my opinion makes the code a bit more structured and readable. I like that java is somewhere in between Python and C. While Python has nearly too less syntax and C too much, I think java is a great middleway to combine the benefits of both. The hardest challenge I faced with java was probably in SoPra as we implemented an online version of the board game called dog. We had to persist everything into a database, and it took some time to get used to database handling in java but in the end we managed it.

_Why is it relevant:_ Everybody has a favorite set of tools and technologies. We love to hear about other people‘s experiences to broaden our horizon.
