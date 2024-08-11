source "https://rubygems.org"

# Core Gems
gem "jekyll", "~> 3.9.2"

# Jekyll Plugins
gem "jekyll-feed"
gem "jekyll-sitemap"
gem "jekyll-include-cache"
gem "jekyll-last-modified-at"
gem "jekyll-redirect-from" # Added for managing redirects

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-include-cache"
  gem "jekyll-last-modified-at"
  gem "jekyll-redirect-from" # Ensure the redirect plugin is included in the plugins group
end

# GitHub Pages Gem
gem "github-pages", "~> 227", group: :jekyll_plugins

# Ensuring the correct version of Ruby is used
ruby '2.7.4'

# Debugging Tools
gem "jekyll-debug", group: :jekyll_plugins
