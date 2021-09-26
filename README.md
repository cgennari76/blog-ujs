# README

Use rails generator to get started:

rails new blog-ujs
rails webpacker:install
bundle add devise
rails generate devise:install
rails generate controller home index #landing page
rails g scaffold post title:string body:text
rails g scaffold comment commenter:string body:text post:belongs_to
rails generate devise User
