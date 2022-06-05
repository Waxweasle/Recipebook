# Recipebook
A program that connects to the Edamam API and pulls recipes that fit the user specified requirements. A GUI created with tkinter allows users to fill in necessary info and displays various recipes in an easy to read format.
## Prerequisites
1. Python 3.0+
## Edamam API set up
1. Create an account at https://developer.edamam.com/edamam-recipe-api
2. Go to Account>Applications>Create New Application> and enter your parameters to get your application id and application keys.
3. Paste this information into `app_id =` and `app_key =` within the get_recipes() method
## How to
Simply run the program and enter the necessary information as prompted by the GUI. All fields **NOT** marked optional must be filled in to contact the API. After searching , results from the Edamam API will be displayed "book style" with "next" and "previous" buttons that allow the user to flick through recipes page by page. If you wish to edit any of the search parameters that are fed into the API, full documentation can be found at https://developer.edamam.com/edamam-docs-recipe-api. The API provides a link to the reipce method which is clickable from the recipe page.
## Future improvements
1. Implementing a "save favorites" feature that saves the users favorite recipes to their machine for quick and easy retrieval.
2. A web scraper to pull the method of the recipe from the origin website(currently not provided by the API) so the user doesn't need to open a link to the page.
