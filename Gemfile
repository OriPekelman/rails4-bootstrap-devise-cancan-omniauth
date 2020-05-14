source "https://rubygems.org"

gem "rails", "~> 5.0.0.0"
gem "mongoid", github: "mongoid/mongoid"
group :assets do
  gem "sprockets-rails", ">= 2.2.0"
  gem "sass-rails", github: "rails/sass-rails"
  gem "coffee-rails", github: "rails/coffee-rails"
  gem "therubyracer", platforms: :ruby
  gem "uglifier", ">= 1.0.3"
end

group :development do
  gem "guard-rspec"
  gem "pry"
  gem "quiet_assets", ">= 1.0.2"
  gem "thin", ">= 1.5.1"
end

group :development, :test do
  gem "zeus"
  gem "rspec-rails", ">= 2.13.2"
  gem "factory_girl_rails", ">= 4.2.1"
end

group :test do
  gem "mongoid-rspec"
  gem "ffaker"
  gem "simplecov", require: false
  gem "database_cleaner"
  gem "rb-inotify", "~> 0.9"
end

gem "jquery-rails", ">= 4.0.1"
gem "turbolinks", ">= 1.1.1"
gem "jbuilder", "~> 1.0.1"
gem "bootstrap-sass", "~> 2.3.0.1"
gem "font-awesome-sass-rails", ">= 3.0.2.2"
gem "simple_form", github: "plataformatec/simple_form"
gem "devise", git: "https://github.com/plataformatec/devise.git", branch: "rails4"
gem "cancan"
gem "omniauth", ">= 1.1.4"
gem "omniauth-github", ">= 1.1.0"
gem "omniauth-twitter", ">= 0.0.16"
gem "hashugar", github: "alex-klepa/hashugar"
