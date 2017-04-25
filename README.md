

  
** You are working on 

+ gem 'mindapp', github: 'kul1/mindapp', branch: 'a241510'

** Requirements

+ Rails 5.1.0rc1
+ Rubygems 2.4.1

** Installation

  + $ gem 'mindapp', may need to uncomment therubyracer
  + $ bundle
  + $ rails generate mindapp:install
  + $ bundle
  + $ rails generate mindapp:mongoid
  + $ rake db:seed, will create initial user:password admin:secret
  + $ when update app/mindapp/index.mm, run rake mindapp:update
