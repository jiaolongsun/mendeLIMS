source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2', '~> 0.3.13'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

# Gems only required in production (eg ssl)
group :production do
  gem 'bartt-ssl_requirement', :require => 'ssl_requirement'
end

# Gems for non-production environment (remove extraneous/verbose log messages)
gem 'quiet_assets',     :group => [:development, :staging]
gem 'webrick', '1.3.1', :group => [:development, :staging]

gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'jquery_datepicker'
#gem 'rails3-jquery-autocomplete', git: 'https://github.com/francisd/rails3-jquery-autocomplete'
gem 'rails3-jquery-autocomplete', '~> 1.0.11'

gem 'validates_timeliness', '~> 3.0'
gem 'carrierwave', '~> 0.9'

# Helpers for nested forms
gem 'nested_form'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

# gems from R2.3.8 version
gem "ezcrypto"
gem "cancan", '~> 1.6.4'
