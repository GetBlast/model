source 'https://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils', '~> 1.2', require: false, git: 'https://github.com/hanami/utils.git', branch: 'develop'

platforms :ruby do
  gem 'sqlite3', require: false
  gem 'pg',      require: false
  gem 'mysql2',  require: false
end

platforms :jruby do
  gem 'jdbc-sqlite3',  require: false
  gem 'jdbc-postgres', require: false
  gem 'jdbc-mysql',    require: false
end

gem 'hanami-devtools', require: false, git: 'https://github.com/hanami/devtools.git'
gem 'simplecov', require: false
gem 'codecov',   require: false

gem "rom-sql", :git => "https://8ec097bc737c3edf7b8b7a6d0e5eb00451edd52c:x-oauth-basic@github.com/GetBlast/rom-sql", :branch => 'dry_types_0.12.x'
