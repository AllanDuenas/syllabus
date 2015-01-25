# Programacion Estructurada 1501 syllabus

* **Course:** [PE1501, UPCI]
* **Instructor:** cvh, [cvh.upci@gmail.com](cvh.upci@gmail.com)
* **Need help?**
* Office Hours during [Hacker Hours](http://hackerhours.org/) (see [Meetup page](http://www.meetup.com/hackerhours/events/calendar/) for schedule)

## Course Description
Learn programming in C++ in this course. Topics include understanding of variables, data types, control flow, functions, arrays, build your own libraries and best practices. Discover some of the lesser-known, yet useful, features of the language, and how to debug and improve performance.

Computers are not provided in the lab, at least for now, so you are encouraged to bring a laptop for in-class exercises.


## Course Overview

Please take a look in the document "acerca del curso.pdf"
Topics will be demonstrated through live-code examples.  Additional exercises will completed in-class.

## Homework/Projects

All assignments are listed within the [Course Outline](#course-outline).

### Workflow

1. Fork the repository for the exercise/project (found under [github.com/pe1501](https://github.com/pe1501))
1. Clone the repository to your computer
1. Open the `homeworkDD.cpp` file in your IDE
1. Modify the files to complete your solution
1. Make sure all of your code is committed
1. Push/sync up to GitHub
1. [Create a pull request](https://help.github.com/articles/creating-a-pull-request) on the original repository by the due time (generally the start of the following class)
1. You can continue to push fixes and improvements until the close date (listed in Classes) – just add a comment in the pull request to let me know it's been updated.

When the pull request is created, you should see a message saying that "the Travis CI build is in progress" – this means that your solution is being automatically checked for syntax errors.  If this "build" ends up failing (which will show a red "X"), click through the "details" link and scroll to the bottom to see what the errors were.  Per the [requirements](#requirements) below, please fix the issues and push up the changes.

Feedback will be given in the pull request, so please respond with your thoughts and questions!  You are welcome to open the pull request as the work is still in-progress if you are stuck and want to ask a question.

Note that your solution will also be live at `http://USERNAME.github.io/EXERCISE`.  For exercises with multiple levels/versions, leave a new comment in the pull request saying "Level X finished!" before pushing commits for the next level.

### Requirements

These apply to real life, as well.

* [Travis CI](http://docs.travis-ci.com) build should pass
* Must apply "good programming style" learned in class
* Functions should be "short" (see [Sandi Metz's rules for developers](http://robots.thoughtbot.com/post/50655960596/sandi-metz-rules-for-developers))
* Optimize for readability
* Bonus points for:
* [Automated tests](#test-frameworks)
* Creativity (as long as requirements are fulfilled)

## Course Outline

### Class 1

1. Introduction
* Install GitHub for [Mac](https://mac.github.com) or [Windows](https://windows.github.com)
* Sign up for GitHub
1. Student checklist:
* Access [NYU Classes](https://newclasses.nyu.edu) page, where grades will be posted
* [Documentation](https://wikis.nyu.edu/display/nyuclasses/Student+Quick-Start)
1. Explain how slides work
1. Get through `echo_exercise` slide
1. GitHub workflow
* Walk through [workflow](#workflow)
* Create pull request on [students repository](https://github.com/advanced-js/students)
1. Get through "self_executing_functions" slide

#### Homework

* Read [JavaScript Garden](http://bonsaiden.github.com/JavaScript-Garden/)
* Finish up and submit [echo](https://github.com/advanced-js/echo) and [countdown](https://github.com/advanced-js/countdown) exercises
* Complete [blink](https://github.com/advanced-js/blink) exercise

## Pairing Tips

* Three people is possible, but two works best
* Agree on an editor and environment that you're both comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to both people

## Resources

### Required Reading


### Recommended Reading

#### Specific Topics


#### GitHub

* Git and GitHub
* [Official GitHub Help](https://help.github.com/)
* [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
* GitHub Pages
* [Official site](http://pages.github.com/)
* [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)


## Grading

* Class Participation – 40%
* Homework, project, exercises – 60%

## Statements on Plagiarism

### SCPS

> We takes plagiarism very seriously and regards it as a form of fraud.  The definition of plagiarism that has been adopted by the School of Continuing and Professional Studies is as follows: "Plagiarism is presenting someone else's work as though it were one's own.  More specifically, plagiarism is to present as one's own words quoted without quotation marks from another writer; a paraphrased passage from another writer’s work; or facts or ideas gathered, organized, and reported by someone else, orally and/or in writing.  Since plagiarism is a matter of fact, not of the student's intention, it is crucial that acknowledgement of the sources be accurate and complete.  Even where there is not a conscious intention to deceive, the failure to make appropriate acknowledgement constitutes plagiarism.  Penalties for plagiarism range from failure for a homework or project to dismissal from the course.

### Instructor

Reuse and building upon ideas or code are major parts of modern software development.  As a professional programmer you will never write anything from scratch.  This class is structured such that all solutions are public.  You are encouraged to learn from the work of your peers.  I won't hunt down people who are simply copying-and-pasting solutions, because without challenging themselves, they  are simply wasting their time and money taking this class.

Please respect the terms of use and/or license of any code you find, and if you reimplement or duplicate an algorithm or code from elsewhere, credit the original source with an inline comment.

### License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">work</span> and all other materials under https://github.com/advanced-js are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
