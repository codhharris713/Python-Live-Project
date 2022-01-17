# Python-Live-Project
 
# Introduction
 
 This was a two week project developing a web application using Django Framework. It consisted of a bunch of different hobbies which each sub-app tracked a different hobby that we got to choose ourselves. I created a app based on different sushi recipes with users being able to create, edit, delete, and save the recipes to a database.
 <br>
 <br>
# Building the basic app
 <br>
 I created the new app for the project, and named it appropriately for what I was going to be tracking.
 Frist I created the base and home templates in a new template folder and included block tags.
Then I added function to the views to render the home page and registerd the urls with the Main App, linking my app's home page to the projects home page by adding a image link. Last on this step I then added basic styling to the base and home.

<br>

# Creating a model 
<br>
I created a model and added migration and planned out all the categories I wanted to track for my object, including a objects manager for accessing the database.
 To create a user input form, I created a model form that included any inputs the user needed to make. I added a template for my app folder and added a views function that renders the create page and utilizes the model form to save the item to the database. The user could then add to the database throught my template rather then through admin.
 
 <br>
 
 # Display information from the database
 <br>
 I then created a new HTML page and linked it from my home page and added a function that gets all the items from the database and sends them to the template. 

<br>

# Edit and Delete functions
<br>
I added a functioning edit page for any item in the database and had the ability to delete that item. I used the model forms and instances to display the content of a single item from the database and had the views function to send the information for the single item. I then included the option to delete an item with a confirmation that the user wants to delete.
