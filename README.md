# real_world_math_backend README

This is frontend section. will need a the backend to this project which you can find here: 

https://github.com/superHotStuff/real_world_math_frontend

## Video Walkthrough

https://www.youtube.com/watch?v=labv9iRqKQo&feature=emb_logo

## tools used

React/Redux, Javascript, Ruby on Rails, React router

## features

Api that fetches a random inspirational quote.
Users will get a random question from the backend database.
Users can sign in or sign up to post comments under a question.

## Overview

This project was made with goal of being multuple choice question and answer for real world math problems. However, questions right now are very basic as i'm still building out some features.

## Installation

Fork and clone repo

    $ git clone https://github.com/superHotStuff/real_world_math_frontend
    $ git clone https://github.com/superHotStuff/real_world_math_backend

Using two terminals, switch to each respective directory

    $ cd real_world_math_frontend
    $ cd real_world_math_backend

Backend terminal instructions: 

    $ bundle install
    $ rails db:migrate
    $ rails db:seed
    $ rails s

Frontend terminal instructions: 
    
    $ npm install
    $ npm start

## Usage

    Default home page will give a random quote from an api for inspiration

    You can sign up or sign in via the nav bar button at the top to store already answered questions, and also leave comments underneath a given question

    The get question button will give a question with multiple choice questions

## challenge

Most challenging aspect of this project was changing data through redux.

## future implementations

 ui overhaul.
 Email to be sent out weekly to user with new question.

## Contributing

This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
