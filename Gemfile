source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'
gem 'rails', '~> 6.0.0.rc1'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 4.3'
gem 'sass-rails', '~> 5'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'pg', '0.18'
gem 'figaro'
gem 'simple_form', '~> 5.0.0'
gem 'slim-rails'
gem 'high_voltage', '~> 3.0.0'
gem 'browser_warrior', '>= 0.11.0'
gem 'sidekiq'
gem 'kaminari', '~> 1.1.1'
gem 'rails-i18n', '~> 6.0.0.beta1'
gem 'mina', '~> 1.2.2', require: false
gem 'mina-ng-puma', '>= 1.3.0', require: false
gem 'mina-multistage', require: false
gem 'mina-sidekiq', require: false
gem 'mina-logs', require: false
group :development do
  gem 'rails_apps_testing'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_bot_rails'
end

group :test do
  gem 'database_cleaner'
  gem 'launchy'
end
