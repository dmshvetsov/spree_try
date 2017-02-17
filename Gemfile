source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '5.0.1'

gem 'jquery-rails', '4.2.2'
gem 'pg', '0.19.0'
gem 'puma', '3.7.0'
gem 'sass-rails', '5.0.6'
gem 'uglifier', '3.0.4'

gem 'spree', '3.2.0.rc2'
gem 'spree_auth_devise', '3.2.0.beta'
gem 'spree_gateway', '3.2.0.beta'

group :development, :test do
  gem 'byebug', '9.0.6', platform: :mri
end

group :development do
  gem 'listen', '3.0.8'
end
