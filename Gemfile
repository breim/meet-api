# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |_repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.4'

# My Gems
gem 'figaro'
gem 'has_scope'
gem 'pg_search', '2.1.4'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem 'jbuilder'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem 'image_processing', '~> 1.2'
group :development, :test do
  gem 'byebug'
  gem 'debug'
end

group :development do
  gem 'letter_opener_web', '~> 1.0'
  gem 'rubocop'
  gem 'rubocop-performance'
end
