%div(style="text-align:center")
  = image_tag "logo_mindapp.png"
  
%h2 You are working on 
%ul
  %li gem 'mindapp', github: 'kul1/mindapp', branch: 'f241502'

%h2 Requirements
%ul
  %li Rails 5.1.0rc1
  %li Rubygems 2.4.1

%h2 Installation
%ul
  %li gem 'mindapp', may need to uncomment therubyracer
  %li bundle
  %li rails generate mindapp:install
  %li bundle
  %li rails generate mindapp:mongoid
  %li rake db:seed, will create initial user:password admin:secret
  %li when update app/mindapp/index.mm, run rake mindapp:update