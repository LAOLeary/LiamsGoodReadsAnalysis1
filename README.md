# LiamsGoodReadsAnalysis1
The goal of this project was to determine general trends for aggregated user activity on GoodReads for books originally published in English.

This Python data analysis project uses the best data set available for GoodReads books:
https://www.kaggle.com/jealousleopard/goodreadsbooks

I took assistance from the following Kaggle project which gives a great overview on generic data analysis used:
https://www.kaggle.com/vaishnavikarelia/what-s-your-next-book?rvi=1

There are major limitations of this project's dataset. As you can see from my data cleaning process, 
I removed all books with fewer than 30 pages, as I found many false entries here (notably a Stephen King one) in the original set.

Also, there are far, far, more books on GoodReads. This data set had less than 250 books written in any language other than English? So there's clearly an anglophone bias in the dataset already. However, this is the largest available data set, and for now should be representative of user activity in the larger set.

GoodReads recently shut down new API requests to gather more data, so this is all we have to rely on until they change their mind on that.
 
