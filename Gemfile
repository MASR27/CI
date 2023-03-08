source "https://rubygems.org"

# Specify the Jekyll version
gem "jekyll", "~> 3.9"

# Activate the Read the Docs theme
gem "just-the-docs"

# Use GitHub pages gem
gem "github-pages", group: :jekyll_plugins

# Set Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-paginate"
end

# Set up plugins for development and production environments
group :development do
  gem "jekyll-sitemap"
end

group :production do
  gem "jekyll-redirect-from"
  gem "jekyll-seo-tag"
end
