source 'https://rubygems.org'
ruby '2.2.1'

gem 'rails', '4.2.1'
gem 'bootstrap-sass', '2.3.2.0'
gem 'sprockets', '2.12.3'
gem 'bcrypt-ruby', '3.1.2'
gem 'faker', '1.1.2'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'
gem 'web-console'
gem 'carrierwave'
gem 'carrierwave'
gem 'rmagick', :require => 'RMagick'

group :development, :test do
  gem 'rspec-rails', '2.13.1'
  gem 'test-unit'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'sqlite3'
  gem 'factory_girl_rails', '4.2.1'
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

gem 'sass-rails', '4.0.5'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '2.5.3'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
end
group :production, :staging do
  gem 'rails_12factor'
end
