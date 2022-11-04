# Recipes

This project demonstrates my skills of utilizing Python Flask and MySQL to interact with the database, as well as using HTML, CSS(Bootstrap) to create and style different pages. 

# Main Features
1. Login and Registration with validation such as:
  Registration: 
    - First name and last name must be at least 2 characters
    - Email must have valid email format
    - Password and confirm password must match
    - User must NOT already exist in the databse. 
  Login:
    - Email must already exist in the database.
    - Password must be checed against the hashed password in the DB for the existing user. 
2. Dashboard
  - Dashboard only displays when the user is logged in, the user will not be able to access the dasbboard page once logged out.
  - A table will appear to show all recipes created from all users, the edit and delete links will only show if the recipe was created by the logged in user.
  - Edit link: renders the edit page for the specific recipe.
  - Delete link: removes the recipe and redirects back to the dashboard page.
  - View recipe link: renders the recipe details page for the specific recipe. 
