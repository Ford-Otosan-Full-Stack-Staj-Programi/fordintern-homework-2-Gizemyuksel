[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/3bErTxjD)
*Patika-Homework-2*

*Project in master branch*


Database tables were created for the Account and Person models. Controller and model definitions were made for these two models. GetAll, GetById, Put, Post, and Delete action methods were defined. Auth operations were performed using Jwt token. Login was performed on the TokenController endpoint. All actions on the AccountController and PersonController are working with the [Authorize] attribute, preventing unauthorized API calls. Only the Login endpoint was left open to unauthorized API calls. The POST method on the AccountController can only be used by users with the Admin role. The AccountId field on the Person model was automatically filled from the session information of the user who made the request. Filtering was done on all actions on the Person controller based on the account ID value in the session.
