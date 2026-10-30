source 'https://rubygems.org'

# Jekyll 4 for local previewing. The published site is built by GitHub with its
# own pinned toolchain, which ignores this file, so the two may differ safely.
gem 'jekyll', '~> 4.3'

# The five plugins listed under "plugins" in _config.yml, all of which the
# github-pages gem used to supply implicitly.
group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-gist'
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
  gem 'jemoji'
  gem 'webrick', '~> 1.8'
end

# Gems that shipped inside Ruby's standard library until 3.4 and are no longer
# bundled, yet parts of the toolchain still expect them on Ruby 4.
gem 'base64'
gem 'bigdecimal'
gem 'csv'
gem 'logger'
gem 'ostruct'

# Windows ships no system timezone database, which Jekyll needs because
# _config.yml sets a timezone. Unix-likes read theirs from /usr/share/zoneinfo.
gem 'tzinfo-data'
