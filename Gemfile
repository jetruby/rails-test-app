source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'capistrano', '~> 3.10.1'
gem 'capistrano3-service'
gem 'capistrano-bundler'
gem 'capistrano-config'
gem 'capistrano-npm'
gem 'capistrano-yarn'


gem 'rails', '~> 5.0.2'
gem 'pg', '~> 0.19'
gem 'puma', '~> 3.0'

gem 'hamlit', '~> 2.8'
gem 'simple_form'

gem 'elasticsearch-model'
gem 'elasticsearch-rails'

# Front-end stuff
gem 'webpacker'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'sass-rails', '>= 3.2'

# Background jobs
gem 'sidekiq', '~> 4.2'
gem 'sidekiq-scheduler', '~> 2.0'
gem 'sidekiq-failures'
gem 'redis-namespace'

group :development, :test do
  # Console
  gem 'rails_dt'
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'letter_opener'
end
