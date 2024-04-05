# Top_10_Movies

This program takes search terms for movies and returns the top ten movies based for that search. For example, if you search for "Movies with alien and space", the result will be,
1. Lighter Than Hare
2. Paper Doll
3. Prey
4. The Attack of the Giant Moussaka
5. 002 Operazione Luna
6. Aunt Rose
7. Space Chimps 2: Zartog Strikes Back
8. The Falling
9. Space Master X-7
10. Metamorphosis: The Alien Factor

The main idea behind the search engine is **cosine similarity** measure. To handle the massive amount of data where the search takes place, **Map Reduce** programming paradigm has been used utilizing Apache Spark on Databricks.

The dataset could be found in here: [CMU Movie Summary Corpus](https://www.cs.cmu.edu/~ark/personas/) 

To run the program: Import the `main.ipnyb` along with the dataset into any Apache Spark environment. Adjust the dataset directory. And you are good to go.