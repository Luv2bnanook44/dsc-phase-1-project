# Movie Industry Trends¶

<p>
    <img src="images/aesthetics.jpg" width="500" height="300" />
</p>

*Sponsored by Microsoft* ;)

**Authors:** [Christos Maglaras](mailto:Christo111M@gmail.com) and [Jamie Dowat](mailto:jamie_dowat44@yahoo.com)

## Overview

In light of Microsoft's desire to expand their enterprise into the movie sector, we have analyzed various aspects of movie data to help develop some insights to help maximize Microsoft's ROI for their potential startup. 

Since we are both relatively unfamiliar with the business end of the industry, supplementary research on the working of the industry as a whole were considered to help drive and focus our analysis. Access sources HERE.

Our insights were from the following categories:
* Budget vs Total Gross 
    * Movies such as **Minions**, **Beauty and the Beast (1991)**, and **Rocky** had the greatest ROI.
* Genre vs Total Gross 
    * The genres that produce (on average the are **Animation, Adventure, and Sci-Fi**.
* Popularity vs Revenue vs Genre
    * **Action** movies are the most frequently correlated to growth in popularity if there is a growth in revenue.
* Movie Runtime
    * For all genres (generally speaking), an optimal run-time is under 120 minutes.
    * More 'serious' genres have a higher runtime limit (before their 'popularity' decreases)
        * For example, Drama films have the highest runtime threshold, at 220 minutes.
        

## Business Understanding

Beginning a new branch of a business is not easy, especially in the entertainment sector. Using existing data from soon to be competitors, Microsoft has an opportunity to jump start their entry into moviemaking that was not available at the time that their competitors built their business. Thankfully Microsoft is one of the leaders of technology worldwide, distribution of the content will be relatively easy as Microsoft's in house Azure servers could be employed. This leads to the possibility of a Microsoft streaming service, which is the route that many competitors have taken. Amazon has Prime Video, Apple has Apple TV+, and Google owns YouTube, which is comparable but not the same class of product. This gives Microsoft a chance to learn from the mistakes of all those preceding it, and to create a product that improves upon all of those points. This notebook's purpose is to provide as much relevant data as is reasonable to aid Microsoft building a business plan towards producing successful movies.

## Unpacking the Data

Data was analyzed from [IMDB](https://www.imdb.com/), [Box Office Mojo](https://www.boxofficemojo.com/), [The Movie Data Base](https://www.themoviedb.org/), [Kaggle](https://www.kaggle.com/rounakbanik/the-movies-dataset?select=movies_metadata.csv) and [The-Numbers.com](https://www.the-numbers.com/).

IMDB, or The International Movie Data Base, is the internets primary source regarding general movie and television data. Since 1990 they have collected data from both professional and public sources, with much of their data being generated from their users activity.

Kaggle is known as one of the most popular websites hosting datasets for use by data scientists, they also create their own content but much of their content is user generated. The main source of data for the Kaggle dataset used in this notebook is IMDB.

Box Office Mojo is an alternate source of data, and was bought by IMDB in 2008.

The Numbers is another alternate source, they aggregate data from the previous sites and more to create datasets of their own. 

# Analysis

*To clarify, 'Total Gross' is the total box office revenue domestically AND internationally.

## Comparing Budget and Total Gross
We found that **Rocky, Beauty and the Beast (1991), and Minions** had the highest Total Gross to Budget Ratio. These three movies can serve as great references for the biggest movie successes (which Microsoft can aim to emulate).

<p>
    <img src="images/scattertop3.png" width="500" height="300" />
</p>

## Comparing Genre and Total Gross

Using the top 5 Genres (determined by genres that had highest Average Total Gross), we focused in on two aspects of the proceeding graph:
1. **The Hunger Games: Catching Fire** is the #1 Sci-Fi movie in 2013 that has the maximum Total Gross to Budget ratio.
2. **Despicable Me 2** is the #1 Animated movie in 2013 that has the maximum Total Gross to Budget ratio.

<p>
    <img src="images/linechartgenreyears.png" width="400" height="300" />
</p>


## Comparing Release Month vs. Total Gross

The Summer Months have the highest average Total Gross.

<p>
    <img src="images/Averagegrosspergenre.png" width="450" height="300" />
</p>


## Runtime Recommendations
In general, movies should stay shorter than 120 minutes.

<p>
    <img src="images/runtime.png" width="400" height="350" />
</p>

# Business Recommendations

* Make **Action** and **Animated** movies a main part of your repertoire.
* For the above genres, releasing the films in the summer months (esp. May) is optimal.
* When choosing what types and how to go about making a given movie, use the movies with highest “bang for your buck” as a reference. (i.e Use "Despicable Me" as a reference for animated movies)



# Next Steps

* Difference between Box Office Mojo Data and tnMovieBudgets was substantial-- ultimately, we used Box Office Mojo because {}, but the top five genres were *different* when usingn tnMovieBudget data.
* Scraping marketing data would've been useful for Microsoft to consider *how* they should divvy up their production budget.
* Examining studio, producer, and actor popularity and/or ROI.

## For More Information
Please review our full analysis in our Jupyter Notebook or our presentation.

For any additional questions, please contact [Christos Maglaras](mailto:Christo111M@gmail.com) and [Jamie Dowat](mailto:jamie_dowat44@yahoo.com)

### Repository Structure

![repo-struct]("images/repo_structure.png")
