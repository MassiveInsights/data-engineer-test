# Massive Insights Python Test
Over the last few years, data engineering has changed from primarily a RDBMs focused role, to more of a programming role. While SQL skills and knowledge of databases is critical to a successful data engineer, so is a solid foundation in programming.

At Massive Insights, our primary language of choice is Python. The following test will focus on Python fundamentals, and your ability to manipulate data with the language. You will need to have python installed on your computer 

## Instructions

Provide solutions to the questions below in file `solutions.py`. Start each solution with a comment containing the associated question number.

Ensure you have saved your work within `solutions.py` and follow the instructions in the main README.md file in order to submit your test.

## Questions

1. Create a Python function to output the following message to the console: `Hello, Massive Insights!`
   
2. Create a Python function to Write the above message to a file name `hello.txt`. The file should be created in a new folder `output` living in the same directory as your `solutions.py` file.
   
3. Create a Python function to Reverse the above message and add it to `hello.txt`. Do not overwrite the contents of `hello.txt`.
   
4. Create a Python function to read and convert the file `json/orders.json` into a csv. The resulting file should be named `orders.csv` and live in folder `output`.
   
5. Given a list of ISBNs, create a Python function to create a csv containing the ISBN, Title, Author, Publisher and Published Date of each ISBN. Use https://openlibrary.org/dev/docs/api/books to acquire this data. The list of ISBNs can be found in `books/isbns.txt`. The resulting csv should live in `output/books.csv`.

