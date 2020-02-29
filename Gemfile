source 'https://rubygems.org'
git_source(:github) do |repo_name|
	repo_name = "#{repo_name}/#{repo_name}" unless repo_name.inclure?("/")
	"https://github.com/#{repo_name}.git"
end

#heroku should use this version of ruby
#ruby '2.3.3'
gem 'rails', '3.2.22'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3', '1.3.13'

#postgres for production db


#12factor for heroku
gem 'rails_12factor', group: :production

#add twitter bootstrap
gem 'bootstrap-sass', '~> 2.0.1'
gem 'activerecord-import'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'test-unit', '~> 3.0'
gem 'puma', '~> 3.12'



#stripe for taking payments
gem 'stripe', :git =>'https://github.com/stripe/stripe-ruby'

gem 'turbolinks', '~> 2.5', '>= 2.5.3'
gem 'jquery-turbolinks'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
