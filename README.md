# Encyclopedia
A simple encyclopedia app that handle user request using restful routing which allowed user to create entry, remove entry, delete existing entry, edit entry and etc.. The server side logic is built using nodeJS and Express.

## How to use
First, run this command to install all the dependencies/libraries needed for this project: 
- npm install

Then, run this command, this will start a server on port 3000:
- node app.js

And now you can access the home page using this url:
- http://localhost:3000/wiki


## Explore The Site
Now, it's time for you to explore the Encyclopedia site and their features

Click Create New Page on the left side bar, will redirect you to a page that allows you to enter title and content, after you enter the required information, you will be redirected to the newly created entry page.

Randomly clicking an entry on the homepage will redirect you to the specific entry page with the title and content. From here, you can choose to edit the entry content by clicking Edit Page at the left side bar, you can also choose to delete entry at down below the page.

That's also a search bar on the left side bar, if you enter something in it, if what you enter is indeed an existed entry, you will be redirected to the entry page, but if it's not, it will still search for related title base on your keyword.

## More resources
https://cs50.harvard.edu/web/projects/1/wiki/

If you wanted to implement this project yourself, this project is originally from the course CS50Web Programming, but keep in mind the course is taught in Python and Django.

## My solution (Node.js, Express.js)
All entries of this web page is store in entries directory and entries files are in .md format.

Thus first, you can refer to util.js on how to read files in directory, how to convert MD content to HTML content. This file contain all the helper functions on this project.

Then, the requests/url paths are handled using restful routing and they are taken care in routes/wiki.js, and the server is listened on app.js. The frontend(templates) are stored in views folder.

Please leave a star when you find this project interesting!