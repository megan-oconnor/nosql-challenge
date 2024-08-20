# nosql-challenge
module 12

**Overview**</br>
Help the editors of a food magazine, Eat Safe, Love, identify where to focus future article on establishments evaluated by the UK Food Standards Agency.

## [NoSQL_setup_starter.ipybn](https://github.com/megan-oconnor/nosql-challenge/blob/main/NoSQL_setup_starter.ipynb)
### Part 1: Database & Jupyter Notebook Set Up
1. Import the data from the [establishments.json](https://github.com/megan-oconnor/nosql-challenge/blob/main/Resources/establishments.json) file.
2. Add database 'uk_food' and the collection 'establishments' to MongoDB.
### Part 2: Update the Database
Make modificatioins to the 'establishments' collection:
- add a new restuarant that opened in Greenwich
- update BusinessTypeID of the new restaurant
- remove establlishments in Dover Local Authority
- convert the string columns, latitude and longitude, to decimal numbers
- convert the string column, RatingValue, to integer numbers

## [NoSQL_analysis_starter.ipybn](https://github.com/megan-oconnor/nosql-challenge/blob/main/NoSQL_analysis_starter.ipynb)
### Part 3: Exploratory Analysis
Answer the following questions:
1. Which establishments have a high hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0?
Convert all results into a Pandas dataframe and print the number of rows and head of the DataFrame.

## Resources
- Dataset: [establishments.json](https://github.com/megan-oconnor/nosql-challenge/blob/main/Resources/establishments.json)
- Database Set Up File: [NoSQL_setup_starter.ipybn](https://github.com/megan-oconnor/nosql-challenge/blob/main/NoSQL_setup_starter.ipynb)
- Database Analysis File: [NoSQL_analysis_starter.ipybn](https://github.com/megan-oconnor/nosql-challenge/blob/main/NoSQL_analysis_starter.ipynb)
