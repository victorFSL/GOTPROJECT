source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.0'
gem 'sqlite3'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'erb_to_slim', '~> 0.0.8'
gem 'slim-rails', '~> 3.1', '>= 3.1.2'
gem 'jquery-rails', '~> 4.3', '>= 4.3.1'
gem 'autoprefixer-rails', '~> 7.0', '>= 7.0.1'
gem 'owlcarousel-rails'
#gem 'simple_form', '~> 3.4'
#gem 'therubyracer', '~> 0.12.3'
#gem 'paperclip', '~> 5.1'
gem 'sprockets-rails', '~> 3.2'
#gem 'oj', '~> 3.0', '>= 3.0.6'
#gem 'searchkick', '~> 2.3'
#gem 'bonsai-elasticsearch-rails', '~> 0.2.0'
gem 'semantic-ui-sass', '~> 2.2', '>= 2.2.10.1'


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13.0'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  ##gem 'rack-mini-profiler', '~> 0.10.2'
  gem "guard", :require => false
  gem "guard-livereload",  :require => false
  gem "rack-livereload"
  gem "rb-fsevent",        :require => false
end

group :production do
  gem 'pg', '~> 0.20.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
