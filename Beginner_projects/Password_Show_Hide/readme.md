showing and hiding password functionality with checkbox by using html css & javascript.

i made show & hide password functionality with checkbox, means when checkbox is checked, password is shown or otherwise password is hide. 
Its simple to make it, when input tag type value is equal to text then password shows and if input tag type value is equal to password then password is hidden.

I just have to change the value of type attribute of input tag, when checkbox is checked. Means, if checkbox is checked then, I just have to change the value of type attribute of input tag, to type text (type=”text”) and
if it is unchecked then change the value of type attribute of input tag is to password (type=”password”).

Here is basic explanation of how we going to make it.

So the input field for password is some looks like this <input type=’password’ name=’password’ placeholder=’Password’> .
Its very simple to make it, just add type=’text’ to show the password and when I want to hide it, just add type=’password’ to the input tag. And to change the type from text to password and password to text, I use javascript. So lets start making.

Show & Hide Password With Checkbox
So first of all, I have created two file with name index.html and index.css. Then link index.css file to index.html. As i said above that i have added javascript for functionality, i have added javascript in index.html file, You can create another file for javascript, if you want and link it to index.html file.

So here below are some steps to make show and hide password with checkbox.

Step 1 : Create basic structure and add boxes.
So first, I added div tag wth classname container, and inside it add div tag with classname box and give styles to it. box is for the input field for password

Step 2 : Add input tags and text.
After that, in div tag with class value box, add 2 input tag (One is for password and another is for checkbox), One div tag to wrap the checkbox and text (‘show password’ ).
See the below code for better understanding.
show and hide password with checkbox design

Step : 3 Add javascript for functionality.
To change type = “text” to type = “password” and from type = “password” to type = “text” , we going to use use javascript. You can add javascript in html file, after the closed body tag or you can added in in a different file. and link to html file. I have added in html file.

simple javascript code that when user click on checkbox, it checks if checkbox is checked or not. If checked than, it make type=”text” and if unchecked it make type=”password” .
show and hide password with checkbox testing

