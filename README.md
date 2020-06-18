<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Books Best Seller Analysis

*Data Analysis, June 2020, Berlin*

## Content
* [Project Description](https://github.com/MilVas/NSM_pancakes#project-description)
* [Question & Hypothesis](https://github.com/MilVas/NSM_pancakes#question--hypothesis)
* [Dataset](https://github.com/MilVas/NSM_pancakes#dataset)
* [Database](https://github.com/MilVas/NSM_pancakes#database)
* [Workflow](https://github.com/MilVas/NSM_pancakes#workflow)
* [Organization](https://github.com/MilVas/NSM_pancakes#organization)

## Project Description

In this project we focussed on the New York Times best seller list and chose to compare it with the list of the most viewed books and books series of Wikipedia. As there are many people that check best seller lists regularly, we wanted to find out if there is a correlation between best seller books of the New York Times list and the most viewed book pages on Wikipedia.


## Question & Hypothesis

As written before, many people check the New York Times best seller list to make their decision on what book they want to buy next. Also people tend to search for the respective book on Wikipedia to get more information about the content.

Our question:
How are best seller books from the New York Times list are interlinked to the most viewed books on Wikipedia?

Our assumption:
We assume that most books that are on the New York Times best seller list are also listed on the Wikipedia page where the most viewed booked are displayed.


## Dataset

To analyze the question, we worked with the data from from different sources that provide us with:

Information about author, title, the date and when a book got on the New York Times best seller list
Ranking of most viewed books and books series on Wikipedia

We used the following source:
* New York Times API (Link APII)
* Wikipedia table, gathered through web scraping (Link Wikipedia table)


## Database

We created two tables from two different sources. The New York Times table was reduced to the most relevant columns and was then merged (by book title) with the Wikipedia table. The final merged table consisted of the following columns:


* author
* title
* ...


## Workflow

The workflow of our project was as follow:
* Gathering possible data sources while defining the topic
* Definition of questions that can be asked/topics that can be analyzed
* Extracting the data through API/web scraping
* Refine the questions that can be asked/topics that can be analyzed with regards to the extracted data
* Merging and cleaning data
* Running analysis with those data to gain insights (to our questions)
* Preparing presentation based on our insights
* Finalizing folder and file structure


## Organization

For communication we mainly used:

* Zoom
* Slack

For the definition of the topic and the remaining tasks we used:

* Google Docs (was used for brainstorming and thinking about questions for the research)
* GitHub repository
* Kanban board (using Trello)

For gathering data, we all had different tasks and worked on our own. We then afterwards discussed how to merge the data so that one person could focus on that. As soon as we had our final table we thought about possibilities to visualize our data properly.
