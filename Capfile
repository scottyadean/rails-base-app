# Load DSL and Setup Up Stages

# Includes default deployment tasks
require 'capistrano/deploy'
require 'capistrano/setup'
require 'capistrano/bundler'
require 'capistrano/rails'

# If you are using rbenv add these lines:
 require 'capistrano/rbenv'
 set :rbenv_type, :system
 set :rbenv_ruby, '2.2.2


# Includes tasks from other gems included in your Gemfile
#
# For documentation on these, see for example:
#
#   https://github.com/capistrano/rvm
#   https://github.com/capistrano/rbenv
#   https://github.com/capistrano/chruby
#   https://github.com/capistrano/bundler
#   https://github.com/capistrano/rails
#
# require 'capistrano/rvm'
# require 'capistrano/rbenv'
# require 'capistrano/chruby'
# require 'capistrano/bundler'
# require 'capistrano/rails/assets'
# require 'capistrano/rails/migrations'

# Loads custom tasks from `lib/capistrano/tasks' if you have any defined.
Dir.glob('lib/capistrano/tasks/*.cap').each { |r| import r }
