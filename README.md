# Api_Rails_6_Boilerplate

Starter for api project with :
- Ruby 2.7.2
- Rails 6.0.4.1
- PostgreSQL 12.3
- Devise-JWT 0.6.0 (Blacklist revocation strategy)
- Namespace for versioning
- Use with any front end Vue/React/Angular/  and others.

## Installation

`git clone git@github.com:xhostcom/api-rails-6-boiler.git`

`cd api-rails-6-boiler`

`bundle install`

`echo DEVISE_JWT_SECRET_KEY=\"$(rake secret)\" > .env`

`rails db:create && rails db:migrate`

 rails s`

Your API is now running on http://localhost:8080

Go to

http://localhost:8080/api/v1/profile

to see json and register message


## Add more!
