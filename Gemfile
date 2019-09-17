source 'https://rubygems.org'

gem 'rails', '5.2.3'

gem 'mysql2', '~> 0.4.5'
gem 'sass-rails', '~> 6.0.0'
gem 'uglifier', '~> 4.1.20'
gem 'generic_form_builder', '~> 0.13.0'

# GDS managed gems
gem 'plek', '~> 3.0.0'
gem 'gds-sso', '~> 14.1.1'
gem 'govuk_admin_template'
gem "govuk_app_config", "~> 2.0.0"

gem 'gds-api-adapters', '~> 60.0.0'

group :test do
  gem 'cucumber-rails', require: false
  gem 'database_cleaner', '~> 1.7.0'
  gem 'factory_bot_rails', '~> 5'
  gem 'govuk-content-schema-test-helpers', '~> 1.6.1'
  gem 'webmock', '~> 3.7.4'
end

group :test, :development do
  gem 'rspec-rails', '~> 3.8.2'
  gem 'rails-controller-testing' # support `expect(..).to render_template(..)` for rails >= 5.0
  gem 'govuk-lint'
  gem 'pry-byebug'
end
