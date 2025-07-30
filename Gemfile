source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-remote-theme"
  gem "jekyll-redirect-from"
end

gem "faraday-retry" if ENV["GITHUB_ACTIONS"] != "true"
gem "webrick" if ENV["GITHUB_ACTIONS"] != "true"
