source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.3'
# Use sqlite3 as the database for Active Record
<<<<<<< HEAD
#gem 'sqlite3'
=======
# gem 'sqlite3'
>>>>>>> 3cbc78c08c909b06691a62efcb5af195178906a4
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "paperclip", "~> 5.0.0"
#Added Paperclip gem For image

gem 'simple_form'
#For creating a new Post

gem 'bootstrap-sass', '~> 3.3.6'
#For Designing Purpose

gem 'devise'
#For Authorization Purpose

gem 'glyphicons-rails', '~> 0.1.2'
#glyphicons

gem 'kaminari', '~> 0.16.3'  
#Pagination

gem 'jquery-turbolinks'
#For New Profile Photo 

gem 'acts_as_votable', '~> 0.10.0'  
#For Liking the Photo

<<<<<<< HEAD

group :development do
  gem 'sqlite3'  
=======
group :development do
  gem 'sqlite3'
>>>>>>> 3cbc78c08c909b06691a62efcb5af195178906a4
end

group :production do
  gem 'pg'
<<<<<<< HEAD
  gem 'rails_12factor' 
=======
  gem 'rails_12factor'
>>>>>>> 3cbc78c08c909b06691a62efcb5af195178906a4
end