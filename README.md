Steps:-
Open your Terminal/Command Prompt on the project’s root folder.
Install the Requirements: pip install -r requirements.txt.
Then, make database migrations: python manage.py makemigrations
python manage.py migrate
And finally, after a successful migration run the application: python manage.py runserver
At last, open up your favorite web browser Go to URL “http://127.0.0.1/[ PORT_NUMBER ]/“
For the Admin Panel credentials, you have to create one with a superuser

**************************************Explanation**********************************************************

This is a library management system it has two types of login one is admin and another is student 
if login to admin panel you will be able to view the books, add the books in the library which include the name of the book, number of books, the author of the books and lastly you can issue the books to the students and see the books that are issues and also see the students.
if login to student panel you will be asked your name , enrollment number, branch and be able to view the issued books to you 
