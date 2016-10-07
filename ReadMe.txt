this is a description that may help u when working with this project 
this project is a blog .. you are free to play with this blog in your browser 
for more understanding .. it is just similar to amy simple blog on tne 
internet .. and i recommend that you try to use every part in it before 
workin with it . 
this project consist mainly from three apps :  
1 - posts 
2 - comments 
3 - accounts
for posts :
you can access posts from /api/posts/ (after the main url) & method get
for create posts method /api/posts/create/ & method post 
for detail /api/posts/slug (slug is a field you make when creating post)
for edit /api/posts/slug/edit
for delete /api/posts/slug/delete
for comments : similar to posts
/api/comments for listing
/api/comments/create for creating
/api/comments/id (the id for that comment)

for accounts : 
/api/users/login
/api/users/register
the method is post ofcourse for both
for getting the token for each user /api/auth/token 
here is example to register from my linux terminal 
curl -X POST -d "username=akef&password=akef1234" http://127.0.0.1:8000/api/auth/token/
i used these two frame works 
for api 
http://www.django-rest-framework.org/
for authentication
https://getblimp.github.io/django-rest-framework-jwt/

you can read the doucumentation and try doing such things as firebase .. 
if you have any question you can put on slack 

i know that i'm bad at simplifying things , sorry , just write your question and i will try to answer 
