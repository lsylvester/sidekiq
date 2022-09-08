source "https://rubygems.org"

gemspec

gem "rake"
gem "redis"
gem "redis-namespace"
gem "redis-client"
gem "rails", github: "ioquatix/rails", branch: "patch-3"
gem "sqlite3", platforms: :ruby
gem "activerecord-jdbcsqlite3-adapter", platforms: :jruby
gem "after_commit_everywhere"
gem "rack", "~> 3.0.0"

# mail dependencies
gem "net-smtp", platforms: :mri, require: false

group :test do
  gem "minitest"
  gem "simplecov"
  gem "codecov", require: false
end

group :development, :test do
  gem "standard", require: false
  gem "pry"
end

group :load_test do
  gem "hiredis"
  gem "toxiproxy"
end
