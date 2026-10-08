source "https://rubygems.org"

# Local development only. GitHub Pages builds the live site with its own
# environment; this Gemfile just needs to produce a matching preview.
gem "jekyll", "~> 3.10"

# Ruby 3.x removed webrick from stdlib; jekyll serve needs it.
gem "webrick"

# Windows has no system timezone database; needed for `timezone:` in _config.yml
gem "tzinfo", ">= 1.2"
gem "tzinfo-data"

# Jekyll 3.x needs the GFM parser explicitly (kramdown input: GFM in _config.yml)
gem "kramdown-parser-gfm"

# Plugins declared in _config.yml (all supported on GitHub Pages)
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
end
