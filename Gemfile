source 'https://rubygems.org'

gemspec

group :development do
  gem 'rake',			    '~> 0.8.7'

  case RUBY_PLATFORM
  when 'java'
    gem 'maruku',	    '~> 0.6.0'
  else
    gem 'rdiscount',	'~> 1.6.3'
  end

  gem 'ore-core',     '~> 0.1.0'
  gem 'ore-tasks',    '~> 0.3.0'
  gem 'yard',		      '~> 0.6.0'
end
