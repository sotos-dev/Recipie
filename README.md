## Recipie is a portfolio app where you can upload, delete, and favorite your food recipies.

## https://this-recipie.netlify.app/

## Functionality:

A) You can upload a recipe with the information below:

1. Recipe name
2. Recipe ingredient/s
3. Difficulty level
4. Preparation time
5. Image of food
6. Recipe description

- The upload form uses real time validation - it's custom written, no form validation libraries were used on this one - Make sure you try it!

B) You can put a recipe in your "favorites" list by clicking the star icon on the recipe card

C) You can delete a recipe by clicking on the trash icon on a recipe card

- If you delete a favorite recipe it is removed from favorites but not from the recipies list
- If you delete a recipe from the recipies list that you had also made favorite before, this recipe is deleted from both recipies list and favorites list.

## Technologies used:

Front-end:
React - with Create-React-App

Backend:
Firebase - Firestore

## Libraries/Packages:

1. firebase -> for the db (firestore)
2. framer-motion -> for the fade in and out of components when they mount/unmount
3. sass -> Makes working with css more flexible
4. uuid -> for auto-generating ids for the uploads
5. react-icons -> for some of the icons used
6. react-spinners -> to show a loading spinner whilst the app is downloaded or data is fetched
7. the-new-css-reset -> for resetting styles for all browsers and make elements consistent

Have fun with it here is the link!

## https://this-recipie.netlify.app/
