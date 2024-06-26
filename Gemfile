source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# [1] Back-End
gem 'rails', '~> 6.1.7', '>= 6.1.7.8'
gem 'ffi', "< 1.17.0"

# [2] Storage
gem 'sqlite3', '~> 1.4.2'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# [2.1] APIs
# JSON APIs 
# gem 'jbuilder', '~> 2.7'

# [4] Deployment
# App server
gem 'puma', '~> 5.0'

# [5] Config
# Caching: Reduces boot time
gem 'bootsnap', '>= 1.4.4', require: false
# Handle Cross-Origin Resource Sharing (CORS)
# gem 'rack-cors'

group :development, :test do
  # [6] Tools
  # Debug
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-rails', '~> 0.3.9'

  # Fixures - Models
  gem 'factory_bot_rails', '~> 6.2.0'
  # Fixures - Fake Data
  gem 'faker', '~> 2.19.0'

  # Linting
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false

  # [7] Testing
  gem 'rspec-rails', '~> 5.0.2'

  # Auto-run on Modifications
  gem 'guard'
  gem 'guard-rspec'
end

group :development do
  # [6] Tools
  # File modifications
  gem 'listen', '~> 3.3'
  # Pre-load app for console, rake and tests.
  gem 'spring'
end

group :test do
  # [7] Testing
  # Integration
  gem 'capybara', '>= 3.26'
  # API Mocking
  gem "webmock", "~> 3.18"

  # [6] Tools
  # Matchers/Helpers for shorten and simple tests
  gem 'shoulda-matchers', '~> 5.1.0'
  # Strategies for cleaning databases
  gem 'database_cleaner', '~> 1.7.0'
  gem 'database_cleaner-active_record', '~> 2.0'
end

# [6] Tools - Windows
# Time Zone info
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
