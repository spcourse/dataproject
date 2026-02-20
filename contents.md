# Project

Until now, we've shown you exactly what to learn and when. The goal of this project is to find your own subject. Something that you're interested about. In the end we want to see that you can learn a new subject by yourself.

We will suggest some possible subjects ([see below](#projects)), but they're only that: suggestions. You can propose your own subject. Are you already working on some data for you studies/work/research? You can use that for this project. Discuss your subject with one of the teachers before you start.

You have very little time for this project. It should not take up more than the equivalent of 1.5 full-time weeks (60 hours). So it is very important to limit the scope of your project.

The project is going to be evaluated based on the following:

* A process book. Here you document the *learning* process. This should be a day-to-day answering the questions: What have you learned? When? How?
* A final product. The Jupyter Notebook final analysis or visualization.
* Project description. A short document (max. 1000 words) of what the project is about. What is the research question? Which data did you use? 
* Final presentation. You do not get a grade for your presentation itself, but you do have to do it, and it gives you a change to demonstrate your final result in person.

The main goal of the project is for you to learn a new technique. So it is important that your work shows clearly what you've learned.

**Every project should start with some (research) question.**

### Timeline

There are four important deadlines to keep in mind:

* First proposal: At the very start you need to submit your first project proposal. I.e., a short document (max: 200 words), describing the idea of your project (this includes the ersearch question). After submitting it, you need to come in to class it in person. We will evaluate how realistic/challenging the idea is. In case it becomes clear during the discussion that the porposal is not suitable, we ask you to submit a new proposal.
* Second proposal \[optional\]: A new proposal if the first one was not approved.
* Proof of concept: Halfway the project we ask you to sumit a proof of concept. After submitting you will have to come to class again to discuss your progress. You don't have to have all the work fnished, but you should have made substantial progress at this point.
* Final result: After submitting the final version you will present your results during the final presentations.

**It is improtant to meet the deadlines and come in for disucssion**, otherwise you will not be able to finish the course. If you run into issues with these deadlines, contact us as soon as possible! 

### Process book

At the start of the project, create a process book in which you keep track of your progress during the project. Note that it is not necessary to describe in detail what you have been working on every day. Just describe your most important findings and challenges during the project. And document the resources you've used (documentation, data resources, tutorials, video's etc.). Some things to keep in mind:

1. **Don't forget the process book.** Maintain it every day you've worked on the project. This is the main way for us to see what you've learned and is an important part of the evaluation.
2. **Don't use it for everything.** Don't spend too much time on your process book! Ten minutes every day you've worked on the project on this, should be more than enough.
3. **Keep it simple and short.** Use simple language, short sentences, and be as straightforward as possible when documenting your learning process.
4. **Create a simple template.** In order to organize your process book, it is nice to create and use a template:

    * Date of entry:
    * What I've worked on:
    * What problems I encountered:
    * What I learned:
    * Which resources did I use:

### Projects

Whatever project you're going to do. Bear in mind:

1. **Keep it simple.** Sixty hours is not a lot of time. This is not a thesis. Learning a new technique already takes a lot of time, so keep the project itself simple.
2. **Learn something new.** Make sure you use something (a library, algorithm, concept) that hasn't been discussed in the course already.
3. **Use GitHub for storing and sharing your code.** Make regular GitHub backups (don't forget to push to remote) to make sure you don't loose your code. And use the GitHub repository to share your code with us.

### Suggested projects

The suggestions below are meant as an inspiration. You can do the project as described, you can make it your own, or you can even think of your own project.

* Mine book descriptions from Goodreads to generate keywords. *Learn* to use the spaCy NLP-library and TF-IDF. [more...](/project/goodreads)
* Make interactive plots to understand the development of life expectancy and fertility for different countries between 1964 and 2013. *Learn* to use the Bokeh visualization library [more...](/project/development)


### Final project grade

Your project will be evaluated on 4 criteria: Research Question/Project Goal, Complexity, Novelty/Learning, Quality. For each you can get between 0 and 3 points. And they all contribute equally to the final grade. I.e, $$grade = \frac{question + complexity + novelty + quality}{12} \times 9 + 1$$

* **Research Question / Project Goal**: Is the goal of your project clear? Does it answer a clear question? Points:
    * **3 pt. Clear purpose of project**
        * The project states a **clear, focused goal *or* research question** (so it doesn't have to be formulated as a question, as long as it has a clear objective).
        * The question can be answered (or goal can be acheived) with available data and methods.
        * The goal logically guides the data processing, analysis, and final outputs.
    * **2 pt.Mostly clear**
        * A goal or question is present but somewhat **broad or loosely framed**.
        * Connection between goal and chosen methods is visible but not clearly defined.
    * **1 pt.Vague or weak**
        * A general subject is mentioned, but no clear goal defined.
        * The project is exploratory or lacks direction.
    * **0 pt. No goal**
        * No clear question, goal, or problem description.
* **Complexity**: How difficult was the project? Points:
    * **3 pt. High**
        * Complex data sourcing:
            * Uses **multiple data sources**,
            * and/or uses **multiple formats** (CSV, JSON, APIs, scraping),
            * and/or includes **non-trivial data transformations** (merging, cleaning, feature creation).
        * Complex data use:
            * Implements interactive visualisation, advanced analysis, or custom tools,
            * and/or does a thorough in depth analyses of the data. 
    * **2 pt. Moderate**
        * Uses one dataset with **several transformation/processing** steps.
        * Produces multiple meaningful visualisations or summary statistics.
        * Some design choices require elaborate reasoning.
    * **1 pt. Low**
        * Uses a simple dataset with only basic operations.
        * One or two straightforward plots or analyses.
        * Very similar to work done in the modules.
    * **0 pt. Minimal**
        * Simply reads data and produces one basic plot or output.
        * No real processing, transformation, or design choices.
        * Identical to solutions from modules.
* **Novelty / Learning**
    * **3 pt. Significant new learning**
        * Student explores a **new method, library, *or* concept** not covered in the modules.
        * Demonstrates understanding by **implementing *or* adapting** it independently.
    * **2 pt. Some new learning**
        * Student uses **slightly unfamiliar** methods or libraries, but *largely from tutorials*.
        * Some adaptation beyond simple copy-paste.
    * **1 pt. Minimal new learning**
        * Uses only concepts from the modules or that are trivial.
        * New elements are limited to calling a simple function from an imported package.
    * **0 pt. None**
        * No new skills/concepts.
* **Quality**
    * **3 pt. Strong**
        * Code runs and is well-organised. It is clear how to reproduce the results and elaborate on them.
        * Reporting is clear, structured, and interprets results meaningfully.
        * Visualisations and outputs support the stated goal.
        * The project feels coherent from question to conclusion.
    * **2 pt. Good**
        * Correct runs.
        * The code is mostly well readable.
        * Reporting is understandable but may lack clarity or structure in places.
        * Results mostly align with the goal.
    * **1 pt. Weak**
        * Code has inconsistencies or errors but still produces some results. It doesn't run as intended or it is not clear how to run the code.
        * Reporting is incomplete, unclear, or superficial.
        * The project feels disjointed.
    * **0 pt. Poor**
        * Code does not run at all or parts are missing.
        * Reporting is missing or extremely minimal.


</details>

### Final project presentation

There is a presentation for the final project. This presentation is compulsory but **not graded**. The goal is to show your fellow Data Processing students what you’ve been working on. Please keep the following in mind:

* The presentation can be informal. You may use slides, but you can also present directly from your notebook.
* The presentation may **not exceed 10 minutes**. This means you won’t have time to go into extensive technical detail.
* Remember that you’re presenting to your fellow students. They have the same programming background as you, but they may not know much about the topic of your project.

Make sure we understand:

* what your research question or topic is,
* which new concepts you had to learn,
* and what the main results of your project are.