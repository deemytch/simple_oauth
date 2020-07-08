source 'https://rubygems.org'

gem 'jruby-openssl', :platforms => :jruby
gem 'rake'

group :test do
  gem 'backports'
  gem 'coveralls'
  gem 'mime-types', '~> 1.25', :platforms => [:jruby, :ruby_18]
  gem 'rest-client', '~> 1.6.0', :platforms => [:jruby, :ruby_18]
  gem 'rspec'
  gem 'rubocop', '>= 0.28', :platforms => [:ruby_19, :ruby_20, :ruby_21]
  gem 'simplecov'
  gem 'yardstick'
end

gemspec
