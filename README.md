#### ECOR 1042 Fall 2021 _T008_data_analyzer_ Version 1.0 12/06/2021
Copyright &copy; 2021 Nam Duong, Audrey Lun, Hamzah Shaikh and Sangsongthong Chantaranothai, Carleton University, Faculty of Engineering and Design. All rights reserved.

The project can be reached at:  
**Email:** namduong@cmail.carleton.ca

### Description:
------------

- The project contains a user-interface program that allows a user to load, add, remove, search, filter and sort books in a dataset, by inputting a series of commands. The dataset is loaded from a csv file containing the information of the books including title, publisher, genre, page count, rating, author, and language. 

- The project is made up of four files:  
 P5_T008_load_dataset.py  
 T008_P2_search_modify_dataset.py  
 T008_P3_sorting.py  
 T008_P4_booksUI.py  

### Installation:
------------

Recommended to use python 3 version 3.9.7 or later.  
Only built-in python modules are used. No external modules must be loaded.

For older versions of python, it is advised not to use under any version older than 3.8.  
This program has been tested under python 3.9.7 so any older version might not behave as expected. 

### Usage:
------------

Start the program by running the python file, _T008_P4_booksUI.py_, or running it with a command prompt window.  
Once running, input commands from the command list displayed, and follow the prompts.  
 - There is no error control, therefore, if a non-integer value is entered when prompted for an integer value, the program will end.
 - If a file name that is inputted does not exist, or if the file is not in the same directory as the program files, the program will end.
 - All project files must be in the same directory.
 - The file being loaded must be a csv file. Hint: include _.csv_ when loading the file with the file name.

**Example of program being run:**

\> python T008_P4_booksUI.py  

1-  Command Line L)oad file  
2-  Command Line A)dd book  
3-  Command Line R)emove book  
4-  Command Line F)ind book by title  
5-  Command Line NC) Number of books in category  
6-  Command Line CA) Categories for an author  
7-  Command Line CB) Categories for a book title  
8-  Command Line G)et book  
&emsp;R)ate A)uthor P)ublisher C)ategory CT) Category and Title CR) Category and Rate  
9-  Command Line S)ort book  
&emsp;T)itle R)ate P)ublisher C)ategory PA)ageCount  
10- Command Line Q)uit  

Enter a command: g  
--File not loaded--  
Enter a command: d  
--No such command--.  
Enter a command: L  
Enter the filename to load: My_Books.csv  
\----------  
1-  Command Line L)oad file  
2-  Command Line A)dd book  
3-  Command Line R)emove book  
4-  Command Line F)ind book by title  
5-  Command Line NC) Number of books in category  
6-  Command Line CA) Categories for an author  
7-  Command Line CB) Categories for a book title  
8-  Command Line G)et book  
&emsp;R)ate A)uthor P)ublisher C)ategory CT) Category and Title CR) Category and Rate  
9-  Command Line S)ort book  
&emsp;T)itle R)ate P)ublisher C)ategory PA)ageCount  
10- Command Line Q)uit  

Enter a command: S  
Enter subcommand: R  

{'title': "Antiques Roadkill: A Trash 'n' Treasures Mystery", 'author': 'Barbara Allan', 'rating': '3.3', 'publisher': 'Kensington Publishing Corp.', 'page_count': '288', 'language': 'English', 'genres': 'Fiction'}  
{'title': 'Deadpool Kills the Marvel Universe', 'author': 'Cullen Bunn', 'rating': '4.2', 'publisher': 'Marvel Entertainment', 'page_count': '96', 'language': 'English', 'genres': 'Comics'}  
{'title': 'The Painted Man (The Demon Cycle, Book 1)', 'author': 'Peter V. Brett', 'rating': '4.5', 'publisher': 'HarperCollins UK', 'page_count': '544', 'language': 'English', 'genres': 'Fiction'}  
{'title': 'Edgedancer: From the Stormlight Archive', 'author': 'Brandon Sanderson', 'rating': '4.8', 'publisher': 'Tor Books', 'page_count': '226', 'language': 'English', 'genres': 'Fiction'}  
{'title': 'Sword of Destiny: Witcher 2: Tales of the Witcher', 'author': 'Andrzej Sapkowski', 'rating': '4.8', 'publisher': 'Hachette UK', 'page_count': '400', 'language': 'English', 'genres': 'Fiction'}  
\----------  
1-  Command Line L)oad file  
2-  Command Line A)dd book  
3-  Command Line R)emove book  
4-  Command Line F)ind book by title  
5-  Command Line NC) Number of books in category  
6-  Command Line CA) Categories for an author  
7-  Command Line CB) Categories for a book title  
8-  Command Line G)et book  
&emsp;R)ate A)uthor P)ublisher C)ategory CT) Category and Title CR) Category and Rate  
9-  Command Line S)ort book  
&emsp;T)itle R)ate P)ublisher C)ategory PA)ageCount  
10- Command Line Q)uit  

Enter a command: A  
Enter the title of the book: Fahrenheit 451  
Enter the author of the book: Ray Bradbury  
Enter the publisher of the book: Ballantine Books  
Enter the genre of the book: Fiction  
Enter the language of the book: English  
Enter the rating of the book: 4  
Enter the page count of the book: 256  
The book has been added correctly.  
\----------  
1-  Command Line L)oad file  
2-  Command Line A)dd book  
3-  Command Line R)emove book  
4-  Command Line F)ind book by title  
5-  Command Line NC) Number of books in category  
6-  Command Line CA) Categories for an author  
7-  Command Line CB) Categories for a book title  
8-  Command Line G)et book  
&emsp;R)ate A)uthor P)ublisher C)ategory CT) Category and Title CR) Category and Rate  
9-  Command Line S)ort book  
&emsp;T)itle R)ate P)ublisher C)ategory PA)ageCount  
10- Command Line Q)uit  

Enter a command: Q  

### Credits:
------------

**Audrey Lun 101222487** - load_dataset, print_dictionary_category, add_book, remove_book, to_list, 
sort_books_pageCount, check_command, load_file, add, remove, find, menu

**Hamzah Shaikh 101250214** - get_books_by_rate, find_books_by_title, get_books_by_author, 
sort_books_category, sort

**Sangsongthong Chantaranothai (Gexter) 101182380** - get_books_by_publisher, check_category_and_title, 
all_categories_for_book_title, sort_books_descending_rate, sort_books_publisher, get

**Nam Duong 101236836** - get_books_by_category, get_book_by_category_and_rate, get_author_categories, 
sort_books_title, sort_books_ascending_rate, num_book_in_cat, author_cat, book_cat

