source 'https://rubygems.org'
ruby '2.0.0'
gem 'rails', '4.0.0'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'devise'
gem 'figaro'
gem 'mysql2'
gem 'simple_form', '>= 3.0.0.rc'
gem 'activeadmin', github: 'gregbell/active_admin', branch: 'rails4'
gem 'carrierwave'
gem 'mini_magick'
gem 'awesome_print'
gem 'therubyracer'
gem 'anjlab-bootstrap-rails', :require => 'bootstrap-rails', :github => 'anjlab/bootstrap-rails', :branch => '3.0.0'
gem 'fog'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :rbx]
  gem 'hub', :require=>nil
  gem 'quiet_assets'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end

group :production do
  gem 'thin'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner', '1.0.1'
  gem 'email_spec'
end
