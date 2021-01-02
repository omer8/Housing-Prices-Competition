Housing Prices Competition
===========================================

Project Title
-------------
Housing Prices Competition
.. image:: https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png
   :width: 633
Date created
------------
3/01/2021

Creator
-------
- `Omar Mohamed <https://github.com/omer8>`__.

This data set contains the following features:
----------------------------------------------
 
   -  id : The Book ID
   -  title : The Book Title
   - rating : The rating given to the book
   - user : The User ID
  
Project Workflow:
-----------------
Scraping Data:

We scrape the data from `Goodreads API <https://www.goodreads.com/api/index#review.show>`__. which gets the books in a member shelf.

Recommender System:

This is a Collaborative filtering Recommender system that we used to build intelligent recommender systems
that can learn to give better recommendations as more information about users is collected.

This recommender take a book name and then recommend to you the most relevant books to it.


