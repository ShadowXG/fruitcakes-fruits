# Fruitcakes Full CRUD Full Stack App

- Use Express to build a server
- Use mongoose to communicate with mongoDB
- Full CRUD functionality on our fruits resource
- User Authentication
- The ability to add comments to fruits
- (Maybe gather data from a 3rd party API)

This app will start as an API, that receives request and sends JSON responses, but eventually we will add a views layer that will render html in our browser.

This is an MVC application
We're using the MVC system for organizing our code.
This breaks our app down into these three parts.
MVC stands for
- Models
- Views
- Controllers

Models- All of our data, what shap it's in and what resources we're using(models), and how our resources relate to one another

Views - All the different ways we can see our data, whether it's as a JSON response, or an catual HTML response, this determines how our dat can be viewed by the user.

Controllers - Tell us what we can do and connect our views an our models. We can think of our routes as our controllers, because the determine how a user can interact with our resources.

## How we talk about what we're doing

We're ussing express framework to build a server, in which we are using mongoose to process our requests and run CRUD operations using a mongoDb database.

What we're building is a REST api, that runs full CRUD operations on a single resource. (This will change, eventually)

## What is REST???

## Describe REST and list the various routes

| **URL**           | **HTTP Verb**|**Action**|
|-------------------|--------------|----------|
| /fruits/          | GET          | index    
| /fruits/:id       | GET          | show     
| /fruits/new       | GET          | new      
| /fruits           | POST         | create   
| /fruits/:id/edit  | GET          | edit     
| /fruits/:id       | PATCH/PUT    | update   
| /fruits/:id       | DELETE       | destroy  