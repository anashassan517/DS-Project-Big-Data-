# DS-Project-Big-Data-

This is the link below for the Dataset.
https://drive.google.com/drive/folders/1yXP0tlmGdZnoaJaz-QiFmXyBXzq2F-jJ?usp=sharing

INTRODUCTION:
In the world of computer science, data structure refers to the format that contains a collection of data values, their relationships, and the functions that can be applied to the data. Data structures arrange data so that it can be accessed and worked on with specific algorithms more effectively. 
Our data set that we have taken from the Kaggle website is around 1GB consists of different books record/details some of which are book IDs, book titles, book author names, book publisher’s names, published month, published day, published year, count of reviews, language, page numbers, ratings, description, ISBN, etc. Items, such as names, numbers, etc. can be stored in memory in a sorted order called binary search trees or BSTs. And some of these data structures can automatically balance their height when arbitrary items are inserted or deleted. Therefore, they are known as self-balancing BSTs. Further, this type can have different implementations, like the B-Trees, AVL trees, and red-black trees. That’s why we have chosen AVL trees and used them to store our good reads book data sets.

FUNCTIONS:
In our data set, there are lots of invalid data that’s why we have stored our invalid data in the linked list because we have also to store the track of our invalid record and on the other hand, we have stored our valid records in AVL trees. We have made different functions that read data from different files and store them in AVL trees.
1)	Processing:
Out of many functionalities, one is that we have done processing on our useful/valid record in such a way that the user enters his/her desired names of different books and we give different suggestions and recommendations to the user and then load the record of that entered book in a dynamic array.

2)	Filtering:
Another functionality that we have implemented is filtering. That useful record of the particular book that the user enters which is loaded in a dynamic array is then passed through a process of filtering. The attributes of the book record such as a month, day, year and rating, etc have been filtered. 

3)	Further Filtering in published month attribute:
We have also done some further filtering in the published month attribute of the book record such as moth-wise sorting of books, particular month books record, and the most recent month published books.  

4)	Further Filtering in published year attribute:
We have also done some further filtering in the published year attribute of the book record such as year-wise sorting of books, particular year record of books, and the most recent year published books. 

5)	Further Filtering in rating book attributes:
We have also done some further filtering in the rating book attribute of the book record such as books with the higher rating, books with the lowest ratings, and books with the user’s desired rating.  

6)	Filtering Invalid Records:
The invalid book records that we have stored in the linked list go through the process of filtering such as we can print the names of those books stored in the linked list that contains an invalid ISBN or we can also print the names of books that contains an invalid published month, day or year or we can also print the names of those books that contains invalid page numbers.


