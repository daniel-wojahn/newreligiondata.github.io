source 'https://rubygems.org'

gem "jekyll", "~> 4.4.1"

# If you want to use GitHub Pages, remove the "gem 'jekyll'" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
  gem "jekyll-sitemap", "~> 1.4.0"
  gem "jekyll-feed", "~> 0.17.0"
  gem "jekyll-seo-tag", "~> 2.8.0"
  gem "jekyll-paginate", "~> 1.1.0"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Required for Ruby 3
gem "webrick", "~> 1.8"