source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem "rails", "~> 7.0.8"
gem "sqlite3"

gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap"
gem "devise"
gem "mailgun-ruby"
gem "puma"
gem "react-rails"
gem "redis"
gem "sassc-rails"
gem "simple_form"
gem "sprockets", "~> 4.0"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"
gem "webpacker"

group :development, :test do
  gem 'pry'
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "rspec-rails"
  gem "rspec_junit_formatter"
end
