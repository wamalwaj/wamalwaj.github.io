# Define gem source
source "https://rubygems.org"

# GitHub Pages gem for Jekyll compatibility
gem "github-pages", "~> 232", group: :jekyll_plugins

# Timezone data for Windows systems
gem "tzinfo-data"

# Windows file monitoring dependency (only needed for Windows users)
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-paginate"     # Enables pagination for blog posts
  gem "jekyll-sitemap"      # Generates sitemap.xml for SEO
  gem "jekyll-gist"         # Embeds GitHub gists
  gem "jekyll-feed"         # Creates RSS feed
  gem "jemoji"              # Adds emoji support
  gem "jekyll-include-cache" # Caches included files for faster builds
  gem "jekyll-seo-tag"      # Improves SEO metadata
end
