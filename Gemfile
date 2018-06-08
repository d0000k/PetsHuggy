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

group :production do 
	gem 'pg'
	gem 'rails_12factor'
end

group :development, :test do 
	gem 'sqlite3'
end



group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end