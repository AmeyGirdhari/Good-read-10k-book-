# Good-read-10k-book recommendation system.

This is a book recommendation system, it recommendes book that is similar to query book of user.for this project k-nearest neighbors algorithm is used.
project mainly divided into 5 parts

## 1.Dataset
## 2.Data operations
## 3.Data visulations
## 4.Methodoloy
## 5.Predictions

## 1.Dataset:
for this problem statement data is taken from kaggle goodbook-10k data set. URL:https://www.kaggle.com/zygmunt/goodbooks-10k
this dataset contains 5 files
* ratings.csv contains ratings given by users for different the books
* toread.csv = provides IDs of the books marked "to read" by each user
* books.csv has metadata for each book (goodreads IDs, authors, title, average rating, etc.)
* book_tags.csv contains tags/shelves/genres assigned by users to books. 
* tags.csv translates tag IDs to names.

## 2.Data Operations
In data preprocessing stage ,Data cleaning plays very import role.without cleanning the data we cannot go further. so to clean this data the program checks duplicated entries present in the data and then drops it from the dataset.
for algorithm we neeed whole data to be in single file,For this two csv files are merged(tags.csv & book.csv) t on similar columns.

## 3.Data Visulations
It is very crucial step for making decisions about the data. in this part several plots for various features present in the data were plotted. from this plots trend  present in the data can be observed.

## 4.Methodology
This project consist of  content based recommendation system for books. it is mainly based on  the tags associated with the books which are assigned by its readers.using this tags algorithm can recommended  books which are similar to user input. the input is in the form of book title.k-nearest neighbors algorithm is used in this part.20 nearest neighobrs(i.e.based on cosine distance) are selected from the data based on the tags.this steps ensures that the selected book have similar content. these 20 books are aranged in the desending order of the reviews.this step suggesd the books with higher ratings from the selected 20 books.  

## 5.Predictions
 5 books are recommended which are similar to input query by user. 
