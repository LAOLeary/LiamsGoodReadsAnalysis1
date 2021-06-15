# Liam's GoodReads Analysis 1
The goal of this project was to determine general trends for aggregated user activity on GoodReads for books originally published in English.

This Python data analysis project uses the best data set available for GoodReads books:
https://www.kaggle.com/jealousleopard/goodreadsbooks

I took assistance from the following Kaggle project which gives a great overview on generic data analysis used:
https://www.kaggle.com/vaishnavikarelia/what-s-your-next-book?rvi=1

**IMPORTANT**
There are major limitations of this project's dataset.
First, it contains just under 10,000 books written in English. This clearly is less than the total number of books. For perspective, GoodReads has removed
to this minute 1,915,672 books from the platform (as "NOT A BOOK") due to them not being 'real books' or being censored for content, which you can see here: https://www.goodreads.com/author/show/1000834.NOT_A_BOOK.

As you can see from my data cleaning process, I removed all books with fewer than 30 pages, as I found many false entries here (notably a Stephen King one) in the original set.

This data set had less than 250 books written in any language other than English? So there's clearly an anglophone bias in the dataset already. It's unclear what bias was used to pick English language books. However, this is the largest available data set, and for now should be representative of user activity in the larger set.

GoodReads recently shut down new API requests to gather more data, so this is all we have to rely on until they change their mind on that.
