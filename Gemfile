source "https://rubygems.org"

# For local previews only: run `bundle exec jekyll serve`.
#
# GitHub Pages builds the live site with its own gems. The usual "github-pages"
# gem requires Ruby below 4.0, so this uses Jekyll directly. That makes local
# previews a newer Jekyll than the live site, so check the live site after
# changes to layouts or plugins.

gem "jekyll", "~> 4.3"
gem "webrick"

# No longer bundled with Ruby
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"

# Windows only: timezone data and file watching
gem "tzinfo-data"
gem "wdm", "~> 0.2", platforms: [:windows]

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-redirect-from"
end
