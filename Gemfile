source "https://rubygems.org"

# Declare your gem's dependencies in view_source_map.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

gem "rails", ENV["RAILS_VERSION"] if ENV["RAILS_VERSION"]

# jquery-rails is used by the dummy application
gem "jquery-rails"

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# nokogiri 1.7 requires Ruby version >= 2.1.0
gem "nokogiri", "1.6.8.1" if RUBY_VERSION < "2.1.0"

# To use debugger
# gem 'ruby-debug'

gem "rspec-rails"
