source 'http://rubygems.org'

gem 'rails', '3.1.0.rc6'
gem 'pg'

group :assets do
  gem 'sass-rails', "  ~> 3.1.0.rc"
  gem 'coffee-rails', "~> 3.1.0.rc"
  gem 'uglifier'
end

gem 'jquery-rails'

group :development do
  # Better documentation
  gem 'tomdoc', :require => false

  # Testing emails
  gem 'mailcatcher', :require => false

  # Deployment
  gem 'capistrano', :require => false
  gem 'capistrano-ext', :require => false
end

group :development, :test do
  gem 'ruby-debug19' if RUBY_VERSION.include? '1.9'

  # Placed here so generators work
  gem 'rspec-rails'
  
  # Opening webpages during tests
  gem 'launchy'

  # Testing Javascript
  gem 'jasmine', '~> 1.1.0.rc2'
end

group :test do
  # Core Testing
  gem 'capybara', '~> 1.0.0'
  gem 'fabrication'

  # Test coverage
  gem 'rcov', :require => false
  
  # Test feedback
  gem 'autotest'
  gem 'rspec-instafail', :require => false
  gem 'fuubar'
end
