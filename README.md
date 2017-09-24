# docker-rails2
willing to create a beautiful container to code with Ruby on Rails




## Resources
 - https://robots.thoughtbot.com/rails-on-docker
 
 
 
 ### Db management
  - docker-compose run web rake db:setup    #first db setup
 - docker-compose run web rake db:reset     #reset data migrated
 - docker-compose run web rails db:migrate  #run migrations incrementally