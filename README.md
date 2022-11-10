# Title; Microsoft's New Movie Studio
Authors: Zainabu Cherotich Rono

# Overview
The presentation will highlight Data exploration from various sources to determine the movies that Microsoft can invest in for their new studio. This will be based on three key points;

# Business Problem

How can Microsoft determine the nature of Studio that it can set up for it to create movies that are widely consumed and makes financial sense to the business?

# Questions to consider:
1. What is the most consumed movies across the globe?
2. What is the most rewarding movies, businesswise?
3. What is the best kind of studio to set up?

# Why picked the data for analysis?
The datas picked are as below;
1. bom.movie_gross-csv file
2. imdb.title.basics-csv file
3. imdb.title.ratings-csv file

These files are from box office, which are a great representation of movies that are sold internationally. As such, it will enable Microsoft understand the nature, the entertainment level, the income and kindl of movies they need to invest in so as to remain competitive in the industry.


# Why the questions?

They will enable Microsoft to answer the reason behind creating a studio, while they combine entertainment with business sense.

# The Data
The three key datas are derived from box office, which is known to be the best seller of movies in 2000s. Ourdata is based on this, thus, a better way to keep abreast.

The three files contain categories of information from box office, imdb basics and imdb ratings. The mixture of the three will give us details on ratings of movies, watchtime minutes, titles, domestic and foreign income and year the movies were produced. 

The target variables are majorly the ratings, the genre and income both locally and internationally.

Properties of the variables are as follows;
1. ratings-float
2. genre-object
3. domestic_gross-float
4. foreign_gross-float

# Methods
The data will be analysed using pandas. The csv file will be converted to a dataframe, which will then enable us to analyse in form of pd.
Pandas is an easy way to analyse CSV files since it introduces statistical features that can help join and aggregate data easily and create a summary out of the data.
Additionally, it adopts various visualization tools that are equally important for the analysis. 

# Results
The analysis was carried out in five categories as follows;
1. Histogram of genres that have higher gross-to check top ten performing movies in box office
2. Relationship between genres and total_gross-To check the top five most watched genres, with higher pay
3. Relationship between genres and ratings-To check relationship between ratings vis a vis genres
4. Relationship between total gross and ratings-To check relationship between ratings and income
5. Relationship between Ratings and Runtime minutes and total gross

# Conclusion
Recommendations
1. The top-five movies doing good in box office are Drama, Horror, Mystery, Thriller and Action. They have high ratings, which translates to higher gross.
2. While producing studio, Microsoft should consider combining 2-3 kinds of genres from the top five, since a combination of two or more have higher ratings and higher gross as compared to individual gender. The movies should be between 100-150 minutes, which have better ratings.
3. A24 is the most rewarding kind of studio.

# For more Information
For any additional questions, please contact name & email, Zainabu Rono, zainabu.rono@student.moringa.com

# Repository Structure

├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-student.ipynb    <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code

