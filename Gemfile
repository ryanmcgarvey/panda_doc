source 'https://rubygems.org'

# Specify your gem's dependencies in panda_doc.gemspec
gemspec

gem "bundler"
gem "rake"
gem "faraday"
gem "faraday_middleware"
gem "virtus"
gem "representable"

group :test do
  gem "codeclimate-test-reporter", require: false
end

group :development, :test do
  gem "rspec",   "~> 3.4"
  gem "byebug"
end
