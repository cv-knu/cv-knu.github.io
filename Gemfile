source "https://rubygems.org"

# This site vendors the Minimal Mistakes theme source directly into the repo
# (see _layouts/, _includes/, _sass/), so it is built with plain Jekyll rather
# than the theme gem. Plugins below must match the `plugins:` list in _config.yml.
gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-include-cache"
end

# WEBrick is no longer bundled with Ruby 3+, but `jekyll serve` needs it.
gem "webrick", "~> 1.8"

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
