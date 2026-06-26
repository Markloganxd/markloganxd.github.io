source "https://rubygems.org"

gem "jekyll", "~> 4.4.1"

# jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# windows does not include zoneinfo files, so needs the tzinfo-data gem
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# apparently makes filewatching faster for windows
gem "wdm", "~> 0.1", platforms: :windows

# for launching a local server
gem "webrick"