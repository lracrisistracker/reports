guard 'livereload' do
  watch(/^_site/)
end

require 'guard/jekyll_plus/config'
jekyll_plus_options = {}
guard 'jekyll-plus', jekyll_plus_options do
  watch(Guard::JekyllPlus::Config.new(jekyll_plus_options).watch_regexp)
end
