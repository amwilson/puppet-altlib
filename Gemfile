source ENV['GEM_SOURCE'] || 'https://rubygems.org'

group :test do
  gem 'rake'
  gem 'puppet', ENV['PUPPET_VERSION'] || '~> 3.4.0'
  gem 'rspec-puppet', :git => 'https://github.com/rodjek/rspec-puppet.git'
  gem 'puppetlabs_spec_helper'
  gem 'simplecov'
end

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'vagrant-wrapper'
  gem 'puppet-blacksmith'
  gem 'guard-rake'
end