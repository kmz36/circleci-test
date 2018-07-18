source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
gem 'mysql2'
# Use Puma as the app server
gem 'puma', '~> 3.0'
gem 'puma_worker_killer'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'
gem 'slim-rails'

# for elastic search
gem 'elasticsearch-rails'
gem 'elasticsearch-model'
gem 'elasticsearch-dsl'

gem 'swagger-blocks'

gem 'rails_admin'
gem 'settingslogic'
gem 'draper'
gem 'active_model_serializers'

gem 'active_hash'

# aws-sdk
gem 'aws-sdk'

#state machine
gem 'aasm'

# user a1uthorization
gem 'jwt'
gem 'omniauth'

#resize
gem 'rmagick'

# twillio
gem 'twilio-ruby'

#check
gem 'devise'

gem 'activerecord-import'

gem 'sidekiq'
gem 'sidekiq-cron'
gem 'foreman'

gem 'sentry-raven'
gem 'pundit'

gem 'shrine'
gem "image_processing"
gem "mini_magick"

gem "stripe"

gem "icalendar"

gem "kaminari"

# AES encryption
gem "attr_encrypted", "~> 3.0.0"

gem "bundler-audit"

gem 'seed-fu'

group :production do
  gem 'ddtrace'
end

gem "google-cloud-translate"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem "rspec"
  gem "rspec-rails"
  gem "parallel_tests"
  gem "rspec_junit_formatter"

  # mail
  gem 'letter_opener'

  # factory_bot
  gem 'factory_bot_rails'
  gem 'database_cleaner', '1.6.1'
  gem 'elasticsearch-extensions', '0.0.29'
  gem 'dotenv-rails'
  gem "vcr"
  gem 'webmock'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-doc'
  gem "shrine-memory"
  gem 'mock_redis'
  gem 'timecop'
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'rails-erd'
  gem 'sniffer'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
