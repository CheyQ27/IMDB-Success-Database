# IMDB Database Hypothesis testing
## Throughout this project I will extract, transform, and load data into MySQL database to answer business questions with the certainty of hypothesis testing.

**Author**: Cheyenne Quann

### Business problem:

what makes a movie successful?

### Data:
IMDB and The Movie Database (TMDB) data containing features like title, revenue, rating, budget, and many more. The data was extracted in csv or json files through API calls.


## Methods
- Extract and filter raw data from IMDB and TMDB
- Visualize the data to explore and find underlying trends
using seaborn and matplotlib
- Delve into data, formulating hypotheses and using AB testing to answer questions posed about the data

## Results
There has proven to be a significant impact on the revenue films bring in based on their budget, runtime and rating 
### Here are examples of how to embed images from your sub-folder


#### Visual 1 
![barplot](rating.png)

> This plot shows a distinct difference between the revenue based on rating 

#### Visual 2 
![barplot](data:image/png;base64,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)
> This plot shows a distinct difference between the revenue based on budget 

#### Visual 3 
![barplot](runtime.png)
> This plot shows a distinct difference between the revenue based on runtime 

## Recommendations:
If one would like to create blockbuster films I would suggest sticking to two hour plus runtimes children's films and if possible apply a large budget


## Limitations & Next Steps

My main limitation is this project was that I had to filter a lot of data and some of my samples were smaller than I would have preferred

### For further information


For any additional questions, please contact **Cheyenne.quann@gmail.com**
 
