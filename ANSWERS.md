## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
The nil represents the fact that there should be nothing entered in the text box yet.


2. Go to `localhost:3000/teachers` in your browser; why does this not work?
There is no GET route for /teachers yet.


3. What type of request did your browser just perform?
The browser performed a POST request.


4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
We ended up at the localhost:3000/teachers URL.


5. Why does `localhost:3000/teachers` work now?
Because we are POSTing to /teachers, not GETting from /teachers and there is
a route already defined for POSTing to /teachers.
