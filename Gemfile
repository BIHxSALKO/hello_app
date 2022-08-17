source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.5'

gem 'rails',      '6.1.4.6'
gem 'puma',       '5.3.1'
gem 'sass-rails', '6.0.0'
gem 'webpacker',  '5.4.0'
gem 'turbolinks', '5.2.1'
gem 'jbuilder',   '2.10.0'
gem 'bootsnap',   '1.7.2', require: false

group :development, :test do
  gem 'sqlite3', '1.4.2'
  gem 'byebug',  '11.1.3', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',        '4.1.0'
  gem 'rack-mini-profiler', '2.3.1'
  gem 'listen',             '3.4.1'
  gem 'spring',             '2.1.1'
end

group :test do
  gem 'capybara',           '3.35.3'
  gem 'selenium-webdriver', '3.142.7'
  gem 'webdrivers',         '4.6.0'
end

group :production do
  gem 'pg', '1.2.3'
end

# gem 'rails', '6.0.2.1'
# gem 'puma', '3.12.2'
# gem 'sass-rails', '5.1.0'
# gem 'webpacker', '4.0.7'
# gem 'turbolinks', '5.2.0'
# gem 'jbuilder', '2.9.1'
# gem 'bootsnap', '1.4.5', require: false

# group :development, :test do
#   gem 'sqlite3', '1.4.1'
#   gem 'byebug', '11.1.3', platforms: [:mri, :mingw, :x64_mingw]
# end

# group :development do
#   gem 'web-console', '4.0.1'
#   gem 'listen', '3.1.5'
#   gem 'spring', '2.1.0'
#   gem 'spring-watcher-listen', '2.0.1'
# end

# group :test do
#   gem 'capybara', '3.28.0'
#   gem 'selenium-webdriver', '3.142.4'
#   gem 'webdrivers', '4.1.2'
# end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Uncomment the following line if you're running Rails
# on a native Windows system:
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
