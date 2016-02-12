*  ```rails new "App Name" -T```
*  copy Gemfile
*  ```bundle install --without production```
*  ```rake db:create```
*  uncomment ```gem 'rails_12factor'```
*  ```bundle install```
*  ```rails generate rspec:install```
*  ```rails g controller welcome index about```
*  copy routes.rb
*  copy development.rb to config/environments
*  ```rails g devise:install```
*  Add basic flash messages:
```html
<p class="notice"><%= notice %></p>
<p class="alert"><%= alert %></p>
```
*  *optional:* ```rails g devise:views```
*  ```rails g devise user```
*  *optional:* modify migration - confirmation is nice
  * remember to add confirmation to user model
