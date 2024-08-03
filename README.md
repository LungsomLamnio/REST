# Quora Post API
This project is a simple RESTful API for managing Quora-like posts using Node.js, Express, and EJS for templating.

# Features
Create a New Post: Users can create new posts with a username and content.
Read Posts: View all posts or individual posts in detail.
Update Posts: Edit the content of existing posts.
Delete Posts: Remove posts from the list.

# Technologies Used
Node.js: JavaScript runtime for building server-side applications.
Express: Web framework for Node.js to manage routing and middleware.
EJS: Embedded JavaScript templates for server-side rendering.
UUID: For generating unique identifiers for posts.
Method-Override: Allows the use of PUT and DELETE methods in HTML forms.

# Project Structure
Views: Contains EJS templates for rendering HTML pages.
index.ejs: Displays all posts.
new.ejs: Form for creating a new post.
show.ejs: Detailed view of a single post.
edit.ejs: Form for editing a post.
Public: Contains static files like CSS.
Server: Handles routes for creating, reading, updating, and deleting posts.
