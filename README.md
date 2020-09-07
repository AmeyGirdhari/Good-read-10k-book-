# Good-read-10k-book recommendation system.

This is a book recommendation system, it generate predictions for read book.for this project KNN algorithm is used.
project mainly divided into 3 parts

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
In data preprocessing stage data cleaning plays very import role.without cleanning the data we cannot go further. so to cleaned this that i checked duplicated entries present from the data and then droped it from the dataset.
for algorithm we neeed whole data to be in single file,so for this i merged two csv files on similar columns present in both files.

## 3.Data Visulations
It is very crucial step for making decisions about the data. in this part i plotted several plots for various features present in the data. from this plots we are eaisly find the trend in the data.

## 4.Methodology
for this project i created content based recommendation system for books. it is mainly based on tags associated with the books.using this tags algorithm can recommended
few books for read according to users input. user can give input in the form of book title.KNN neighboros algorithm is used in this part.

## 5.Predictions
as user gives input in the form of books title algorithm process it and using cosine distances it predicts the book for the user
