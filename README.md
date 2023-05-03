# Traveling-Web-App


##Screenshots

<p float="left">
  <img src="" width="400" height="350" />
 <img src="" width="400" height="350" />
 <br></br>
  <img src="" width="400" height="350" />
<img src="" width="400" height="350" />
<br></br>
  <img src="" width="700" height="350" />
</p>


 ## Introduction
 A web application that is used as a simple travelling website. The website allows the users to lookup several travelling destinations. Users should
   be allowed to create an account, add places to their “want-to-go list” and search for travelling destinations. 
 ## Components:
 1. Users Login (Main Page):
    + Registered users should be allowed to log in to their accounts using their stored username and
password. If credentials are correct, the user should be redirected to the home page. If an
unregistered user tries to log in an error message should be displayed.
2. User Registration:
   + Users should be allowed to create an account using a username and a password and the users’
information should be stored in a database using MongoDB. If the user tried to register using an
already taken username or left any of the fields empty, an error message should be displayed. After
registration, the user should be redirected to the login page and a message should appear that the
registration was successful.
3. Home Page:
   + The home page is the first page that should be encountered by the users when they log in to their
accounts. It contains several destination categories (Beaches, Mountains, ...etc.) and a button to
view the user’s “want-to-go list”. When the user clicks on any category, they should be redirected
to that category’s page.
4. Category Page:
   + The category page contains all the destinations within this category. When a user clicks on any
destination’s name, they should be redirected to that destination’s page.
5. Destination Page:
   + The destination page contains a description for the destination. The page should also contain an
embedded link for a video describing the destination which can be streamed by the user. Please
don’t copy the video itself to the folder so that it doesn’t exceed the allowed size. Finally, an
“add to want-to-go list” button should be added. The button adds this destination to the user’s
“want-to-go list” in the database. If the destination was already in the user’s list, you should display
an error message and don’t add the duplicate destination.
6.  Want-to-Go List Page:
    + The want-to-go list page contains the destinations that the user previously added using the “Add to
Want-to-Go List” button. A “View Want-to-Go List” button should be added to the home page that
directs the user to their own want-to-go list page.
7.  Search:
    + A search bar will be displayed in all pages except for registration and login pages. The search will
be done using destinations names only. The search result is either a “Destination not Found”
message if the destination was not available in the database, or a list of the destinations that contain
the search keyword in their names (ex: searching for “div” should put “Maldives” as one of the
results). The search results should be clickable and they direct you to that specific destination’s
page.

## Technologies:
   + Node.js:
   + Express:
   + Visual Studio Code (VSCode):
   + MongoDB:
   + Embedded JavaScript (EJS):
