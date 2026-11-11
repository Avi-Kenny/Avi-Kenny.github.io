source "https://rubygems.org"

# Preview locally with `bundle exec jekyll serve`.
#
# The live site is built by .github/workflows/pages.yml with these same gems,
# so local previews match it. The usual "github-pages" gem requires Ruby
# below 4.0, so this uses Jekyll directly.

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
