# Movie-Recommendation-Model
This Model helps to recommend movies
## Loading a Dataset
We can download the dataset from movies.csv
##EDA
We can check whether any columns have null values or not
## Developing model
Here firstly the text data is converted into numeric using Vectorizer
All the columns are not used in developing the model 
The columns that are important are genere,Keywords,Cast,Director,title
Now combining all the column values into one string
use vectorizer to fit and transform the text into numerical values
Now we will be using `Cosine Similarity` to find the relation between the movies
The Higher the similarity value ,the movie can be recommended
Suppose the movie entered by the user is wrong then using difflib we can get closer name which the user meant
Now get the index of the movie name
Then enumerate the list of similarity,then sort it based on higher Similarity value
Then use the index to Display the top 10 or 20 movies 
## Build a Predictive System
Build a predictive system by above steps to check whether it is working or not
