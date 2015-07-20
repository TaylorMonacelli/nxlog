source 'https://rubygems.org'

gem 'berkshelf'

group :integration do
  gem 'rspec_junit_formatter'
  gem 'rubocop-junit-formatter'
  gem 'serverspec'
  gem 'windows_chef_zero'
  gem 'winrm-transport'
  gem 'test-kitchen', '~> 1.4.0'
  gem 'kitchen-vagrant', git: 'https://github.com/gh2k/kitchen-vagrant', 
                         branch: 'boot-timeout'
end

group :development, :test do
  gem 'chefspec'
  gem 'foodcritic'
  gem 'rubocop'
  gem 'rake'
end

group :development do
  gem 'pry', '~> 0.9.0'
  gem 'travis', '~> 1.7.5'
end
