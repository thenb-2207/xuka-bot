source "https://rubygems.org"
git_source(:github) {|repo| "https://github.com/#{repo}.git"}

ruby "2.5.3"
gem "figaro"
gem "jbuilder", "~> 2.7"
gem "mysql2", ">= 0.4.4"
gem "puma", "~> 4.1"
gem "rails", "~> 6.0.3", ">= 6.0.3.4"
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 4.0"

gem "bootsnap", ">= 1.4.2", require: false

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "pry-byebug"
  gem "pry-rails"
end

group :development do
  gem "listen", "~> 3.2"
  gem "rubocop", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
