source "https://rubygems.org"

gem "jekyll-theme-slate", "~> 0.1.1"
gem "minima", "~> 2.5.1"

gem "github-pages", "~> 215", group: :jekyll_plugins

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# kramdown v2 ships without the gfm parser by default. If you're using
# kramdown v1, comment out this line.
gem "kramdown-parser-gfm"

gem "webrick", "~> 1.7"
