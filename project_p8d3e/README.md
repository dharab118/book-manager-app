# Book Manager

**Book Manager** is a **Java desktop application** that provides the user a space to monitor their book collection. It is a simple tracker that stores book details, including the title, author, completion date, and rating of any added book. The application is useful for avid readers who want to oversee their book collection and analyze their reading history. As someone who grew up reading heavily, I am invested in making this application efficient and easy to manage.  

####

**User Stories:** 
- As a user, I want to be able to *add* books to my collection
- As a user, I want to be able to *view* the list of books in my collection
- As a user, I want to be able to *select* a book and view its details (ie. author, rating) 
- As a user, I want to be able to *sort* the list of books by rating (highest to lowest)
- As a user, I want to be able to view my favourite books (ie. 5-rated books)
- As a user, when I select the quit option, I want to be reminded to *save* my current book collection, and have the option to do so, or not
- As a user, when I start the application, I want to be given the option to *load* my book collection from file

####
 **Future Features:**
- users can add personalized notes to any book they add
- users can sort books alphabetically by title and author
- users can enter a "completion date" to any added book
- users can sort books by completion date 
- users can add "in progress/currently reading" books 
- users can remove books from their collection


####
**Phase 4, Task 2**

Fri Apr 01 14:47:12 PDT 2022\
Added book: Jade Legacy \
Fri Apr 01 14:47:21 PDT 2022\
Added book: Recursion\
Fri Apr 01 14:47:23 PDT 2022\
Viewed favourites list\
Fri Apr 01 14:47:47 PDT 2022\
Added book: Bear Town\
Fri Apr 01 14:47:49 PDT 2022\
Viewed favourites list

####
**Phase 4, Task 3**
- The BookManagerApp class and the GUI class have a lot of code duplication. This is because my GUI class essentially replaces my initial BookManager console UI. Though there are still some features solely on the BookManagerApp class that I was unable to incorporate into the GUI for the time being, eventually getting rid of the BookManagerApp class and replacing it entirely with the GUI class would be ideal.
- A lot of my methods rely on sorting functionalities. That is, sorting books alphabetically, identifying which book is selected by the user to get further book details, figuring out which books are favourite books, etc. All of these currently use for loops that have to loop through every book to find the book that matches the user's selection. For a very large book collection, this could be modified to use a different data structure (hash table maybe?). 
