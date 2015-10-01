source 'https://rubygems.org'

gem 'rails', '3.2.19'
gem 'locomotive_cms', '2.5.6', :require => 'locomotive/engine'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
  gem 'compass', '~> 0.12.7'
  gem 'compass-rails', '~> 2.0.0'
end

group :production, :staging do
  gem 'rails_12factor'
  gem 'newrelic_rpm'
end

gem 'unicorn'
