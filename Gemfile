source 'https://mirror.nju.edu.cn/rubygems/'

gem 'jekyll'

group :jekyll_plugins do
  gem 'jekyll-seo-tag'
  gem 'jekyll-paginate'
  gem 'jekyll-email-protect'
  gem 'jekyll-target-blank'
end

gem "webrick", "~> 1.7"

gem 'wdm', '>= 0.1.0' if Gem.win_platform?

if Gem::Version.new(RUBY_VERSION) >= Gem::Version.new('3.2.0')
  gem 'liquid', '>= 4.0.4'
end