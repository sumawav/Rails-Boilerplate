*  ```rails new "App Name" -T```
*  copy Gemfile
*  ```bundle install --without production```
*  ```rake db:create```
*  uncomment ```gem 'rails_12factor'```
*  ```bundle install```
*  copy application.scss (replace application.css)
*  ```rails generate rspec:install```
*  copy spec/rails_helper.rb
*  ```rails g controller welcome index about```
*  copy routes.rb
*  copy development.rb to config/environments
*  ```rails g devise:install```
*  copy application.html.erb
*  *optional:* ```rails g devise:views```
*  ```rails g devise user```
*  *optional:* modify migration - confirmation is nice
  * remember to add confirmation to user model
*  ```rake db:migrate```
