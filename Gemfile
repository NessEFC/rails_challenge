source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'rails', '~> 5.0.3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

# gem 'bcrypt', '~> 3.1.7'
# gem 'capistrano-rails', group: :development
# gem 'redis', '~> 3.0'
# gem 'therubyracer', platforms: :ruby

group :development, :test do
  gem 'awesome_print', require:'ap'
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails'
  gem 'pry'
  gem 'rspec-rails'
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'faker'
  gem 'launchy'
  gem 'selenium-webdriver', '~> 2.53.4'
  gem 'shoulda-callback-matchers', '~> 1.1.1'
  gem 'shoulda-matchers', '~> 3.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
