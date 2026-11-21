# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "rake"
gem "minitest", "< 6"

gem "nokogiri",
    git: "https://github.com/mpokrywka/nokogiri.git",
    branch: "ruby-3.1-v1.19.6"

gem "loofah",
    git: "https://github.com/mpokrywka/loofah.git",
    branch: "ruby-3.1-v2.25.3"

group :rubocop do
  gem "rubocop", ">= 1.25.1", require: false
  gem "rubocop-minitest", require: false
  gem "rubocop-packaging", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
end
