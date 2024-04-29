source "https://rubygems.org"

gem 'github-pages', "~> 231", group: :jekyll_plugins
# this gem provides regeneration support improvements on Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

# Webrick is no longer a bundled gem in Ruby 3.x.
# However it is not included in the spec of jekyll 3.9.5,
# which is provided by github-pages v231 gem
gem "webrick", "~> 1.8"
