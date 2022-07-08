source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.3'
gem 'tzinfo-data', '~> 1.2022', '>= 1.2022.1', platforms: %i[mingw mswin x64_mingw jruby]
gem 'sprockets-rails', '~> 3.4', '>= 3.4.2', :require => 'sprockets/railtie'

gem 'bootsnap', '~> 1.12', require: false

gem 'rack-cors', '~> 1.1', '>= 1.1.1'

gem 'activeadmin', '~> 2.13', '>= 2.13.1'
gem 'sassc', '~> 2.4'

gem 'cancancan', '~> 3.4'
gem 'devise', '~> 4.8', '>= 4.8.1'

group :development, :test do
  gem 'byebug', '~> 11.1', '>= 11.1.3', platforms: %i[mri mingw x64_mingw]

  gem 'rspec-rails', '~> 5.1', '>= 5.1.2'

  gem 'rubocop', '~> 1.31', '>= 1.31.2'
  gem 'rubocop-performance', '~> 1.14', '>= 1.14.2'
  gem 'rubocop-rails', '~> 2.15', '>= 2.15.2'
  gem 'rubocop-rspec', '~> 2.12', '>= 2.12.1'
end

group :development do
  gem 'spring', '~> 4.0'
end

group :test do
  gem 'shoulda-matchers', '~> 5.1'
  gem 'simplecov', '~> 0.21.2'
end
