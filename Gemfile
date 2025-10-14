# frozen_string_literal: true
source "https://rubygems.org"

group :development, :test do
  gem "rake"

  gem "cancancan"
  gem "pundit", ">= 2.5.1"

  gem "draper"
  gem "devise"

  gem "rails", "~> 8.0.2"

  gem "sprockets-rails"
  gem "ransack", ">= 4.4.0"
  gem "formtastic", ">= 5.0.0"

  gem "cssbundling-rails"
  gem "importmap-rails", ">= 2.2.0"
end

group :test do
  gem "cuprite", ">= 0.16"
  gem "capybara"
  gem "webrick"

  gem "simplecov", require: false # Test coverage generator. Go to /coverage/ after running tests
  gem "simplecov-cobertura", require: false
  gem "cucumber-rails", ">= 4.0.0", require: false
  gem "cucumber"
  gem "database_cleaner-active_record", ">= 2.2.1"
  gem "launchy"
  gem "parallel_tests"
  gem "rspec-rails", ">= 8.0.0"
  gem "sqlite3", platform: :mri

  # Translations
  gem "i18n-tasks", ">= 1.0.15"
  gem "i18n-spec"
  gem "rails-i18n" , ">= 8.0.2" # Provides default i18n for many languages
end

group :rubocop do
  gem "rubocop"
  gem "rubocop-capybara"
  gem "rubocop-packaging"
  gem "rubocop-performance"
  gem "rubocop-rspec"
  gem "rubocop-rails", ">= 2.31.0"
end

gemspec path: "."
