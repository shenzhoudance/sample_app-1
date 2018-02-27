source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.6'
# gem 'sqlite3'
gem 'bootstrap-sass'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'

# gem "win32console"
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'sdoc', group: :doc
gem 'rails-controller-testing'
group :development, :test do
  gem 'sqlite3'
  # gem 'web-console'
  gem 'spring'
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
end
group :test do
  gem 'minitest-reporters'
  gem 'mini_backtrace'
  gem 'guard-minitest'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
