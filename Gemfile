source 'https://rubygems.org'

gemspec

# Rack 2.0.x doesn't work on < Ruby 2.2
gem 'rack', '< 2.0'

group :development do
  gem 'rspec',    '~> 2.14.1'
  gem 'cucumber', '~> 2.1'
  gem 'webmock',  '~> 1.17.3'
  gem 'vcr',      '~> 2.6'
  gem 'yard',     '~> 0.8.7'
end

group :metrics do
  gem 'coveralls', '~> 0.8.9'
  gem 'simplecov', '~> 0.10.0'
  gem 'yardstick', '~> 0.9.9'
end
