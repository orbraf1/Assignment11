# Assignment 11
### Hey, my name is Or Braf. First of all, those are the properties of 'users' table from assignment 10:
* user_id - the primary key of this table: int type, auto incremented (ascending order), unique & not null.
* name - varchar type, max length 255.
* email - text type.
### Those are the main things I did in this assignment:
* I created a new route called 'assignment11/users' and added it to the menu of my website. This route returns a JSON format list of users from the table 'users' I created in my DB.
* I created another route called 'assignment11/outer_source' and implemented two ways of extracting a single user from reqres.in website:
  1. Frontend - using a JS file called 'assignment11' and its functions put_user_inside_html() & getUser() which could be activated by click from assignment_11_outer_source.html.
  2. Backend - importing requests in app.py file. In this method I connected the function ass11_outer_source_func() in app.py to the html file assignment_11_outer_source.html. 
  
  both ways led to the same result - showing the picture, name and email of a single user from the list.
