source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "academic-jekyll-theme"

# Required for Ruby 3.4+ (unbundled gems)
gem "csv"
gem "logger"
gem "base64"
gem "bigdecimal"
gem "mutex_m"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
