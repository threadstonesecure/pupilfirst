source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.7'

gem 'active_admin_editor'

gem 'activeadmin', github: 'gregbell/active_admin' # master for rails 4
gem 'jquery-ui-rails', '~> 4.2.1' # Forcing downgrade of jquery-ui-rails from 5.0.0 because of a bug that causes issue with activeadmin master.

gem 'acts-as-taggable-on'
gem 'attribute_normalizer', '~> 1.2.0.b'
gem 'carrierwave'
gem 'carrierwave_backgrounder', git: 'https://github.com/glhewett/carrierwave_backgrounder.git' # https://github.com/lardawge/carrierwave_backgrounder not updated for sucker_punch v1.0 api changes
gem 'cocoon'
gem 'coffee-rails', '~> 4.0.0'
gem 'devise_invitable'
gem 'fog' # required by carrierwave to upload to s3
gem 'jbuilder', '~> 2.0'
gem 'jquery-rails'
gem 'just-datetime-picker'
gem 'mini_magick'
gem 'newrelic_rpm'
gem 'nokogiri'
gem 'omniauth', '~> 1.2.1'
gem 'pg'
gem 'rubypress' # wordpress
gem 'sass-rails', '~> 4.0.3'
gem 'sendgrid_smtpapi'
gem 'sentry-raven'
gem 'slim'
gem 'sucker_punch'
gem 'turbolinks'
gem 'uglifier'
gem 'urbanairship'
gem 'prawn'
gem 'versionist'
gem 'rest-client'
gem 'cancancan', '~> 1.8' # Used to manage administrator types and roles in the ActiveAdmin interface.
gem 'paper_trail' # Logs changes in critical tables, and displays changelog in ActiveAdmin dashboard.
gem 'phony_rails' # Phone number validation and normalization. TODO: Get rid of phony_rails if isn't updated. Last updated was 18/3/2014.
gem 'select2-rails' # Select2 javascript select box improvement library, using in ActiveAdmin interface.
gem 'nilify_blanks' # Sets database fields to nil if blank values are supplied.
gem 'bootstrap-sass', '~> 3.2.0' # Official Sass port of Bootstrap.
gem 'autoprefixer-rails' # Autoprefixer for Ruby and Ruby on Rails.
gem 'simple_form', '~> 3.1.0.rc2' # Simple-form RC2 with support for Bootstrap 3. TODO: Update simple_form to stable when available.
gem 'react-rails', github: 'reactjs/react-rails' # React JS!
gem 'sprockets-coffee-react' # Sprockets preprocessor.
gem 'js-routes' # Routes inside JS.
gem 'validate_url' # URL validation.
gem 'chartkick' # Pretty charts!

group :development do
  gem 'seed-fu', github: 'mbleigh/seed-fu' # check and remove
  gem 'guard'
  gem 'guard-shell'
  gem 'guard-rspec'
  # gem "guard-spork"
  gem 'guard-livereload'
  gem 'childprocess'
  gem 'terminal-notifier-guard'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  gem 'sqlite3'
  gem 'email_spec'
  gem 'factory_girl', require: false
  gem 'factory_girl_rails', '~> 4.0'
  gem 'faker'
  gem 'json_spec', github: 'collectiveidea/json_spec'
  gem 'zeus'
end

group :development, :test do
  gem 'rspec-rails', '~> 2.14.2'
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false
  gem 'dotenv'
  gem 'pry-rails'
  gem 'webmock', require: false
end

group :production do
  gem 'rails_12factor'
  gem 'unicorn'
  # gem 'pdftk-heroku', git: "https://github.com/gouthamvel/pdftk-heroku.git"
end

gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

ruby '2.1.4'
