source 'http://rubygems.org'

gemspec

# dependencies for the dummy app
gem 'rails', '~> 5.1', '>= 5.1.5'
gem 'jquery-rails', '~> 4.3', '>= 4.3.1'
gem 'sqlite3', '~> 1.3', '>= 1.3.13'
gem 'sass-rails', '~> 5.0', '>= 5.0.7'
gem 'uglifier', '~> 4.1', '>= 4.1.6'
gem 'sprockets-rails', '~> 3.2', '>= 3.2.1'

group :development, :test do
  gem 'rspec-core', '~> 3.7', '>= 3.7.1'
  gem 'cucumber-rails', '~> 1.5'
  gem 'capybara-firebug', '~> 2.1'
  gem 'aruba', '~> 0.14.3'
  gem 'database_cleaner', '~> 1.6', '>= 1.6.2'

  # required for travis-ci and linux environments
  gem "phantomjs-linux" if  RUBY_PLATFORM =~ /linux/
end


