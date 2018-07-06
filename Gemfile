source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails',        '5.1.4'
gem 'puma',         '3.9.1'
gem 'sass-rails',   '5.0.6'
gem 'uglifier',     '3.2.0'
gem 'coffee-rails', '4.2.2'
gem 'jquery-rails', '4.3.1'
gem 'turbolinks',   '5.0.1'
gem 'jbuilder',     '2.6.4'
gem 'bootstrap-sass', '~> 3.3.7'
gem 'devise'
gem 'toastr-rails'
gem 'omniauth-facebook'
gem "paperclip", "~> 6.0.0"
gem 'dropzonejs-rails'
gem "figaro", "~> 1.1.0"
gem "webpacker", "~> 2.0"
gem "loofah", '2.2.2'


gem 'sqlite3', groups: %w(test development), require: false
gem 'pg', '~> 0.18', groups: %w(production), require: false
gem 'rails_12factor', group: :production

group :development do
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end