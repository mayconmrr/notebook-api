source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
 
gem 'rails', '~> 5.1.2' 
gem 'sqlite3' 
gem 'puma', '~> 3.7'
gem 'pry-rails'
gem 'rails-i18n', '~> 5.0.0'
gem 'jwt'
gem 'devise_token_auth'
gem 'devise-i18n'
gem 'versionist'
gem 'kaminari' 
gem 'rack-cors'
gem 'active_model_serializers', '~> 0.10.0'

group :development, :test do 
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 3.5'
  gem 'faker'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2' 
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
 
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
