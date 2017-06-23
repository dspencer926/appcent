![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# WDI Project Two

**Build a web-based, CRUD application.**

## Objectives

### Build confidence as a developer by building something of your own.

-  Manage yourself (your time and your emotions) when given a large amount of 
unstructured work.
-  Gain experience building a complex application.
-  Document your work and share it with the public in an effective and articulate 
manner.
-  Learn new technologies by reading documentation and experimenting.

## Tech Requirements

You will be expected to use the following technologies to implement this project:

- **HTML / EJS**: Your HTML should be semantic and valid. Your app uses EJS to render information on the page.
- **Node and Express**: Your app will need to have its own server, built using Express.
- **MVC Pattern**: Your app uses Models, Views, Controllers pattern we have gone over in class.
- **SQL / PG-PROMISE**: Your app will need to persist data. Your app should have **at least two database tables**.
- **`fetch`**: (this can be post-MVP, but highly encouraged) Your app will need to make a third-party API call using `fetch` from the front-end (if you can figure out jQuery AJAX or axios, or any of the other AJAX libraries, feel free to use them).
    - [List of public APIs](https://github.com/toddmotto/public-apis)
    - [Another list of public APIs](https://github.com/abhishekbanthia/Public-APIs)
    - [Yet another list of public APIs](https://github.com/alexpanov/public-apis)
    - TRY OUT your API in postman before you get too emotionally invested in it, to make sure it works the way you think it does...
- **CSS & Design**: Your app should be pleasing to look at. Your design should take usability into account.
- **JavaScript or jQuery**: Your app should have some interactivity on the front end -- DOM manipulation, microinteractions, etc.

Here are a couple of example projects: [Forum](forum.md), [Wiki](wiki.md)

## Process

Resist the urge to jump immediately into coding.  For this sprint we want to 
carefully plan our approach.

- Database - draw out the tables & columns you plan to use in your database.
- Wireframes - detail the flow of your app through simple wireframes
  * You can choose whether you want to whiteboard the wireframes or use some program.
  * Refer back to the [todo app wireframes](https://git.generalassemb.ly/nyc-wdi-ada/HW_U02_D10_TODO_APP-/blob/master/wireframes.md) for an example of what we expect!
- Routes - design the HTTP route architecture of your app
- Set up a github repo and project board for your project
- Find an API that you plan on using and test it out

## Timeline

* *Start Planning* - 5:00PM on Monday, May 1 - Choose a project and begin planning
* *Project Approvals* - 10:00 AM on Tuesday, May 2 - Wireframes (like [the todo app wireframe examples](https://git.generalassemb.ly/nyc-wdi-ada/HW_U02_D10_TODO_APP-/blob/master/wireframes.md)), user stories, database structure.
* *First Check-in* - with squad leader on Wednesday, May 3 - Project board, which API you plan to use.
* *Second Check-in* - 12:00PM on Friday, May 5 - Git repo, routes structure, initial Heroku deployment.
* *Stand Ups* - Every day with your squad leader
* *Presentations* - 10:00AM on Monday, May 7

## Deliverables

- A full CRUD app, with create, edit, and delete functionality, hosted on Heroku
- A public repository on Github.com with your code for this project & a thorough commit history dating back to the beginning of the project
- A thorough `README.md` file that contains the following:
    - The project's name and description
    - Your wireframes and user stories
    - The technologies, APIs, and modules you used and a description of each
    - A code snippet of a part of the app you're particularly proud of
    - Any things you plan to fix or features you plan to add
    - Instructions for downloading the code and running it on localhost
- A presentation in class that:
    - Is 5 minutes in length
    - Shows off the features of the app you're most proud of
    - Explains one or two technical details
    - Explains one or two technical challenges
    - Explains which improvements you might make


## Instructional help
In a push for developer indepedence and self-reliance, we are going to adhere to
[these rules](./asking-for-help.md) 
for recieving help during this project.

## Keep in Mind

**You are going to encounter a ton of unexpected errors and problems.**

Expect to come up against a lot of what can *seem* like roadblocks. Resist the urge to get frustrated. These are amazing learning opportunities. A lot of students treat errors during projects as just getting in the way of "finishing". The point of this project is **not** to finish everything; the point is to integrate your knowledge and deepen your understanding of how to put apps together.

Errors often provide the most valuable source of information about what we don't yet understand. Seeing an error as "it's not working" and randomly changing code until "it works" won't teach you anything. Spending time thoughtfully debugging issues is a fantastic investment that will lead to greater mastery and understanding.

**Pro-Tip** - 'Failure is a temporary state.' :v:

### Project Feedback + Evaluation

* __Project Workflow__: Did you complete the user stories, wireframes as specified above? Did you use source control (Git) as expected for the phase of the program you’re in (detailed above)? Did you submit your project via an issue ticket on GHE?

* __Technical Requirements__: Did you deliver a project that met all the technical requirements? Given what the class has covered so far, did you build something that was reasonably complex?

* __Creativity__: Did you added a personal spin or creative element into your project submission?

* __Code Quality__: Did you follow code style guidance and best practices covered in class, such as spacing, modularity, and semantic naming? Did you comment your code as your instructors have in class?

* __Deployment__: Did you deploy your application to a public url using Heroku?

* __Presentation__: Note: this is not graded, but part of the project. Did you present your app, your code, and your project-making experience clearly and effectively to the class?

* __Total__: Your instructors will give you a score for each section between:

| Score          | Expectations   |
| :------------- | :------------- |
| **0**          | _Incomplete._  |
| **1**          | _Does not meet expectations._ |
| **2**          | _Meets expectations, good job!_ |
| **3**          | _Exceeds expectations, you wonderful creature, you!_ |

This will serve as a helpful overall gauge of whether you met the project goals, but __the more important scores are the individual ones__ above, which can help you identify where to focus your efforts for the next project!

### A Note on Plagiarism

Plagiarism is a serious offense and grounds for expulsion. Our entire policy can be found [in the wiki](https://github.com/ga-students/wdi-nyc-purple-rain-students/wiki/General-Assembly-Plagiarism-Policy).

You are encouraged to ask others, including students, instructors, and stackoverflow, for help. However, it is NOT ACCEPTABLE TO COPY another person's code and submit it as your own. More importantly, it is detrimental to your learning and growth.

All of the following are considered plagiarism or cheating:
* Turning in work that is not your own.
* Turning in someone else's work as your own.
* Hiring, or paying someone to do your work for you.
* Copying words or code without giving credit.
* Building or copying someone else’s idea without their knowledge or giving credit.
* Giving incorrect information about a source.
* Changing words, variable names, etc. but copying the code or files of a source without giving credit.
* Copying so many ideas or code blocks from a source that it makes up the majority of your work, whether you give credit or not.
* Failing to put a quotation in quotation marks.

In an effort to not plagiarize, credit for this content goes to:
* [Plagiarism.org](http://plagiarism.org/), specifically the “plagiarism 101” section.  Content was adapted for code.  For more information, please see:
  * [What is Plagiarism](http://www.plagiarism.org/plagiarism-101/what-is-plagiarism)
  * [Types of Plagiarism](http://www.plagiarism.org/plagiarism-101/types-of-plagiarism)
* [How do I safely write code in my own 'words' and not plagiarize?](http://programmers.stackexchange.com/questions/80167/how-do-i-safely-write-code-in-my-own-words-and-not-plagiarize)
* [Avoiding Plagiarism:  Writing Computer Code](http://www.upenn.edu/academicintegrity/ai_computercode.html)

<!-- Links -->

[forum]: forum.md
[wiki]: wiki.md
[erd]: http://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model
