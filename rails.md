# Ruby on Rails 6
## Managing warnings emitted by Ruby 2.7
> RUBYOPT=-W:no-deprecated rails ...

## CodeCademy references
- [Static Request-Response Cycle](https://www.codecademy.com/articles/request-response-cycle-static)
- [Dynamic Request-Response Cycle](https://www.codecademy.com/articles/request-response-cycle-dynamic)
- [Forms Request-Response Cycle](https://www.codecademy.com/articles/request-response-cycle-forms)
- [Standard Controller Actions](https://www.codecademy.com/articles/standard-controller-actions)

## List of useful commands
Create a new Rail's project using SQLite into 'myapp' directory
> rails new myapp

<br>

Create a new Rail's project using PostgreSQL into 'myapp' directory
> rails new myapp -d postgresql

<br>

Create database
> rake db:create

<br>

Launch the local dev server (with default parameters)
> rails server

<br>

Create several files and a route to 'name'
> rails generate controller Name

<br>

Create a new model 'name' with two attributes 'title' and 'text' of type 'string'
> rails generate model Name title:string text:string

<br>

Run the migration files and create the tables to the database defined in the 'production' section of the `config\database.yml` file
> rails db:migrate RAILS_ENV=production

<br>
