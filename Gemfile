source "https://rubygems.org"

gem "jekyll", ">= 3.8.5"

gem "github-pages", group: :jekyll_plugins

# 깃허브 원격 테마를 사용하기 위한 필수 젬
gem "jekyll-remote-theme"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate", "~> 1.1.0"
  gem "jekyll-sitemap"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# 아래 한 줄이 반드시 포함되어야 합니다.
gem "github-pages", group: :jekyll_plugins
