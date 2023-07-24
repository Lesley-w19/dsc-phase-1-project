# Phase 1 Project

You've made it all the way through the first phase of this course - take a minute to celebrate your awesomeness!

![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project/master/awesome.gif)

Now you will put your new skills to use with a large end-of-Phase project! This project should take 20 to 30 hours to complete.

## Project Overview

This project requires the use Explanatory Data Analyisis to generate insights
for Microsoft as our business stakeholder.
Microsoft sees all the big companies creating original video content and they want 
to get in on the fun. They have decided to create a 'new movie studio', but they don’t 
know anything about creating movies.


### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

For this project, we will use the data under the file path `zippedData/...`. These files contain information about movies. They represent historical data on movies for recent past years, hence this data will be modified for the purpose of the analysis.

The data is contained in three separate CSV files:
1. `bom.movie_gross.csv`: each record represents movie title, with attributes of that movie (e.g. year). The domestic_gross and foreign_gross are represented and each movie listed has a corresponding studio of creation.
2. `title.ratings.csv`: each record represents a movie title, then the Genre and Start year columns with values on the same.
2. `title.basics.csv`: each record represents a movie, with additional columns such as the average ratings


The features of interest for this analysis will be:
`movie_title`: The title (or AKA) of the Movie
`movie_rating`: The rating of the movie
`movie_type`: The genre of the movie


## Deliverables

There are three deliverables for this project:

* A **GitHub repository**
* A **Jupyter Notebook**
* A **non-technical presentation**

Review the "Project Submission & Review" page in the "Milestones Instructions" topic for instructions on creating and submitting your deliverables. Refer to the rubric associated with this assignment for specifications describing high-quality deliverables.

### Key Points

* **Your analysis should yield three concrete business recommendations.** The ultimate purpose of exploratory analysis is not just to learn about the data, but to help an organization perform better. Explicitly relate your findings to business needs by recommending actions that you think the business (Microsoft) should take.

* **Communicating about your work well is extremely important.** Your ability to provide value to an organization - or to land a job there - is directly reliant on your ability to communicate with them about what you have done and why it is valuable. Create a storyline your audience (the head of Microsoft's new movie studio) can follow by walking them through the steps of your process, highlighting the most important points and skipping over the rest.

* **Use plenty of visualizations.** Visualizations are invaluable for exploring your data and making your findings accessible to a non-technical audience. Spotlight visuals in your presentation, but only ones that relate directly to your recommendations. Simple visuals are usually best (e.g. bar charts and line graphs), and don't forget to format them well (e.g. labels, titles).

## Getting Started

Please start by reviewing this assignment, the rubric at the bottom of it, and the "Project Submission & Review" page. If you have any questions, please ask your instructor ASAP.

Next, we recommend you check out [the Phase 1 Project Templates and Examples repo](https://github.com/learn-co-curriculum/dsc-project-template) and use the MVP template for your project.

Alternatively, you can fork [the Phase 1 Project Repository](https://github.com/learn-co-curriculum/dsc-phase-1-project), clone it locally, and work in the `student.ipynb` file. Make sure to also add and commit a PDF of your presentation to your repository with a file name of `presentation.pdf`.

## Project Submission and Review

Review the "Project Submission & Review" page in the "Milestones Instructions" topic to learn how to submit your project and how it will be reviewed. Your project must pass review for you to progress to the next Phase.

## Summary

#### Conclusion
The analysis done for the above dataset chosen yields the following conclusion.
1. The most preferred genre / type of films are the Action-based.
2. In the recent years, the most produced type of films are the Action-based Films
3. The year that returned the most domestic gross is 2018. We are able to relate this with the gemre of film produced that year - which represents the 'Action' based films.


#### Recommendation
From the analysis done above, I would recommend that the Stakeholders:
1. Should consider creating Action-based films
2. Should consider creating films with less runtime runtime in minutes. In doing so, this will yield to  higher ratings from viewers and in turn more revenue for the stakeholder.

#### Limitations of my findings
I agree that the analysis done above doesn't cover all the bases and is a start in solving the business problem, of which type of films should be created by the stakeholder.


To improve this project in the future, I would include more of the datasets provided in the zippedData folder, and provide relationships between the data somewhat recorded. This will in no doubt be useful in providing additional insights and recommendations to the stakeholder.