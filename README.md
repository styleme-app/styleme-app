# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

What I did 
1. rails new StyleMe-app
2. bundle install with bscrypt
3. created an organization on git 
4. created a project there on git
5. in terminal: // ♥ git remote add origin git@github.com:styleme-app/styleme-app.git
6. // ♥ git add .
7. // ♥ git commit -m"test"
8. // ♥ git push origin master
9. Following these steps to add the image uploading functionality through a gem called paperclip - 
git says it is deprecared and redirected me to use this instead 
https://guides.rubyonrails.org/active_storage_overview.html
// ♥ rails active_storage:install
// ♥ rails db:migrate

Below are my models: 

User has many Posts
User has many Stylists, through Posts

Stylists

Posts the join model
I will probably need to add the avatar later - I am not sure what format it is...
extra source: https://medium.com/@anaharris/how-to-add-image-upload-functionality-to-your-rails-app-9f7fc3f3d042



