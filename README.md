# Rhetort Fort

### [App](http://rhetortfort.surge.sh)
### [Demo](https://youtu.be/vGQjqqLc19Y)

An entertainment app inspired by the games, "Cards Against Humanity" and "Quiplash". Users submit humorous answers to various questions and users vote on the best result.

The answer with the most number of "likes" is declared "Conqueror".

Users can 
1) Login/sign up 
2) Search for questions and read all questions & answers 
3) Submit and delete their answers
4) "Like" answers 

After a user has read/answered a question, an image of "👀🏴" appears on the question card, illustrating that the user has already looked at the question. 

## Frontend Repository
[Rhetort Fort Frontend](https://github.com/Bellex0/RhetortFort-Frontend)

## Ruby Version
ruby '2.6.1'

## Rails Version
rails '~> 6.0.0'

## Database
postgreSQL

pg, '>= 0.18', '< 2.0'

## Gem Dependencies
* bcrypt '~> 3.1.7'
* active_model_serializers '~> 0.10.0'
* rack-cors
* jwt '~> 2.1'
* rest-client, '~> 2.1.0'

## Installation
1) Clone or download this repository to local system
2) Use preferred text editor and/or terminal to navigate into `RhetortFort-API` directory
3) Run `bundle install` (or `bundle i`) in terminal
4) Run `rails db:create` in terminal to create database
5) Run `rails db:migrate` in terminal to initialize database
6) Run `rails db:seed` in terminal to seed database with starter data
7) Run `rails s` in terminal to run server in browser at http://localhost:3000/
8) Install and run [Rhetort Fort Frontend](https://github.com/Bellex0/RhetortFort-Frontend)
