source 'http://rubygems.org'

#gem 'bson', '1.3.2'
gem 'rails', '3.2.11'
gem 'jquery-rails'
gem 'rake'


gem 'quality-measure-engine', :github => 'pophealth/quality-measure-engine', :branch => 'develop'
gem 'health-data-standards',:github => 'pelargir/health-data-standards', :branch => 'medaxion'


#gem 'test-patient-generator', :git => 'https://github.com/pophealth/test-patient-generator.git', :branch => 'develop'
#gem 'test-patient-generator', '~> 1.2.0'

#gem "delayed_job_mongoid_web", :git => 'https://github.com/rdingwell/delayed_job_mongoid_web.git', :branch => 'develop'

gem "mongoid_rails_migrations" , "~>1.0"

gem 'highline'
gem 'state_machine'

gem 'devise', '~> 2.0'
gem 'simple_form'

gem "prawn"
gem "pdf-reader", '0.9.0'

gem 'thin', :platforms => [:ruby]
gem 'carrierwave'
gem 'carrierwave-mongoid', :require => 'carrierwave/mongoid'
gem 'cancan', '~> 1.6.7'


gem 'mongoid-grid_fs', '~> 1.7.0' #:git=>'https://github.com/ahoward/mongoid-grid_fs.git'

gem 'nokogiri' , '1.5.6'

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

group :test, :develop do
	gem 'pry'
  gem 'pry-nav'
  gem 'turn', :require => false
  gem 'minitest'
  gem "tailor"
  gem 'simplecov', :require => false
  gem 'mocha', :require => false
  gem 'webmock'
end

group :production do
  gem 'therubyracer', :platforms => [:ruby]
  gem 'therubyrhino', :platforms => [:jruby]
end


