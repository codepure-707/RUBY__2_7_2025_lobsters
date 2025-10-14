source "https://rubygems.org"

gem "rails", ">= 8.0.2"

# database and caching
gem "solid_cache", ">= 1.0.7"
gem "sqlite3"
gem "trilogy"

# jobs
gem "solid_queue", ">= 1.2.0"
gem "mission_control-jobs", ">= 1.0.2"

# rails
gem "activerecord-typedstore"
gem "importmap-rails", "~> 2.2", ">= 2.2.0"
gem "propshaft", ">= 1.2.0"
gem "scenic", ">= 1.9.0"
gem "scenic-mysql_adapter"
gem "scenic_sqlite_adapter"
gem "sentry-rails", ">= 5.25.0"
gem "typeid"

# js
gem "json"

# deployment
gem "actionpack-page_caching"
gem "puma"

# security
gem "bcrypt"
gem "rotp"
gem "rqrcode"

# parsing
gem "commonmarker", "<1"
gem "htmlentities"
gem "pdf-reader"
gem "nokogiri"
gem "parslet"

# perf
gem "flamegraph"
gem "memory_profiler"
gem "rack-mini-profiler", ">= 4.0.1"
gem "stackprof"
gem "prosopite"

gem "builder" # for rss
gem "faker" # for factory data and /cabinet
gem "oauth" # for linking accounts
gem "mail" # for parsing incoming mail
gem "sitemap_generator" # for better search engine indexing
gem "svg-graph", require: "SVG/Graph/TimeSeries" # for charting, note workaround in lib/time_series.rb
gem "rexml" # no release for https://github.com/lumean/svg-graph2/pull/48/files
gem "rack-attack" # rate-limiting
gem "lograge" # for JSON logging
gem "silencer" # to disable default logging in prod

group :test, :development do
  gem "benchmark-perf"
  gem "brakeman"
  gem "capybara"
  gem "database_cleaner"
  gem "listen"
  gem "letter_opener"
  gem "prism" # rm after https://github.com/presidentbeef/brakeman/issues/1909 closes
  gem "rspec-rails", ">= 7.1.1"
  gem "factory_bot_rails", ">= 6.5.0"
  gem "foreman"
  gem "standard"
  gem "standard-performance"
  gem "standard-rails", ">= 1.3.0"
  gem "super_diff"
  gem "byebug"
  gem "rb-readline"
  gem "vcr"
  gem "webmock" # used to support vcr
  gem "simplecov", require: false
  gem "active_record_doctor", ">= 2.0.0"
  gem "database_consistency", ">= 1.7.27"
end
