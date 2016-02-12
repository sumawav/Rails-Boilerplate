1. ```rails new "App Name" -T```
2. copy Gemfile
3. ```bundle install --without production```
4. ```rake db:create```
5. uncomment ```gem 'rails_12factor'```
6. ```bundle install```
7. ```rails g controller welcome index about```
8. copy routes.rb
9. copy development.rb to config/environments
10. ```rails g devise:install```
11. Add basic flash messages:
```html
<p class="notice"><%= notice %></p>
<p class="alert"><%= alert %></p>
```
12. optional: ```rails g devise:views```
13. ```rails g devise user```
