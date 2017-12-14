source 'https://rubygems.org'

gem 'rails', '5.0.2'

gem 'unicorn', '~> 4.9.0'
gem 'mysql2', '~> 0.4.5'
gem 'sass-rails', '~> 5.0.6'
gem 'uglifier', '~> 3.0.4'
gem 'generic_form_builder', '~> 0.13.0'

# GDS managed gems
gem 'plek', '~> 1.12.0'
gem 'gds-sso', '~> 13.2.0'
gem 'govuk_admin_template'
gem "govuk_app_config", "~> 0.2.0"

if ENV["API_DEV"]
  gem "gds-api-adapters", path: "../gds-api-adapters"
else
  gem 'gds-api-adapters', '~> 47.9.1'
end

group :test do
  gem 'cucumber-rails', require: false
  gem 'database_cleaner', '~> 1.5.3'
  gem 'factory_girl_rails', '~> 4.8.0'
  gem 'webmock', '~> 2.3.2'
end

group :test, :development do
  gem 'rspec-rails', '~> 3.7.2'
  gem 'rails-controller-testing' # support `expect(..).to render_template(..)` for rails >= 5.0
  gem 'govuk-lint'
  gem 'pry-byebug'
end
