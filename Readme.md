#HiipCamp

- Add Landing Page
- Add Campgrounds Page that lists all camprounds

Each Campground has:

- Name
- Image

# Layout and basic styling

- Create our header and footer partials
- add in Bootstrap

# Creating New Campgrounds

- Setup new Campground POST route
- Add in body-parser
- Setup route to show form
- Add basic unstyled form

# Style the campgrounds page

- Add a better header/title
- Make campgrounds display in a grid

# Style the Navbar and form

- Add a navbar to all templates
- Style the new campground form

# Add mongoose

- Install and configure mongoose
- Setup campground model
- Use campground model inside of our routes

# Show Page

- Review the RESTful routes we've seen so far
- Add description to our campground model
- Show db.collection.drop()
- Add a show route/template

RESTFUL ROUTES

# name url verb description

INDEX /campgrounds GET Display a list of campgrouns
NEW /campgrounds/new GET Display form
CREATE /dogs POST Add new campground to DB
SHOW /campgrounds/:id GET shows info about one dog

# Refactor Mongoose Code

- Create a models directory
- Use module.exports
- Require everything correctly

# Add Seeds File

- Add a seeds.js file
- Run the seeds file every time the server starts

# Add the comment model

- Make our errors go away
- Display comments on campground show page

# Comment New/Create

- Discuss nested routes
- Add the comment new and create routes
- Add the new comment form

#Style Show page

- Add sidebar to show page
- Display comments nicely

##Finish Stylish Show Page

- Add public directory
- Add custom stylesheet

##Add User Model

- Install all packages needed for auth
- Define User model

## Register

- Configure Passport
- Add register routes
- Add register template

# Login

- Add login routes
- Add login template

# Logout/Navbar

- Add logout route
- Prevent user from adding a comment if not signed
- Add links to navbar

## Auth - Show/hide links

- Show/hide auth links correctly

## Refactor The Routes

- Use Express router to reorganize all routes

## Users + Comments

- Associate users and comments
- Save author's name to comment automatically

## Users + Campgrounds

- Prevent an unauthenticated user from creating a campground
- Save username+id to newly created campground

## Editing Campgrounds

- Add Method-Override
- Add Edit Route for Campgrounds
- Add Link to Edit Page
- Add Update Route

#Deleteing Campgrounds

- Add Destroy Route
- Add Delete button

#Authorization Part 1: Campgrounds

- User can only edit his/her campgrounds
- User can only delete his/her campgrounds
- Hide/show edit and delete buttons

#Editing Comments

- Add Edit route for comments
- Add EDit button
- Add Update route

#Deleting Comments

- Add Destroy route
- Add Delete buttony

#Authorization Part 2: Comments

- User can only edit his/her comments
- User can only delete his/her comments
- Hide/show edit and delete buttons
- Refactor Middleware

#Adding in Flash

- Demo working version
- Install and configure connect-flash
- Add bootstrap alerts to header
