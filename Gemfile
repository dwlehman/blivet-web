# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~> 3.3.3"

gem "compass"

# Live-reloading plugin
gem "middleman-livereload"

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end

# For faster file watcher updates for people using Windows
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]


#####
# General plugins

# Blog plugin
gem "middleman-blog"
#gem "middleman-blog-drafts"
#gem "middleman-blog-authors"

gem 'middleman-deploy'

# Thumbnailer
#gem "middleman-thumbnailer", github: "nhemsley/middleman-thumbnailer"

# favicon support (favicon PNG should be 144×144)
gem "middleman-favicon-maker"

# HTML & XML parsing smarts
gem "nokogiri"

# Syntax highlighting
gem "middleman-syntax"

# For feed.xml.builder
gem "builder", "~> 3.0"

# Better JSON lib
gem "oj"

# Lock jQuery to 1.x, for better IE support (6 - 8)
# Fixes and features are backported from 2.x to 1.x; only diff is IE support.
# see http://blog.jquery.com/2013/01/15/jquery-1-9-final-jquery-2-0-beta-migrate-final-released/
gem 'rails-assets-jquery', '~> 1'


#####
# Bootstrap

gem "bootstrap-sass"


#####
# Formats

# less (css)
gem "therubyracer"
gem "less"

# asciidoctor
gem "asciidoctor"

# mediawiki
gem "wikicloth"

gem "coderay"
gem "stringex"

# Markdown
gem "kramdown"

gem 'open-uri-cached'

gem 'font-awesome-middleman'

# RSS/Atom parsing
gem "feedjira"

# Sass plugin thingys for styling html lists more easily
gem 'sassy_list'   # for coloring bullets
gem 'SassyLists'   # for list manipulation
