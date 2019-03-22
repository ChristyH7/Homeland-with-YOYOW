# frozen_string_literal: true

source "https://gems.ruby-china.com"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }

gem "coffee-rails"
gem "jbuilder", github: "rails/jbuilder"
gem "jquery-rails"
gem "rails", "~> 5.2.0"
gem "rails_autolink"
gem "sass-rails"
gem "sprockets"
gem "turbolinks", "~> 5.0.0"
gem "uglifier"

gem "sanitize"

gem "pg"
gem "pghero"

gem "rack-attack"

gem "bootstrap", "~> 4.1.0"
gem "font-awesome-rails"
gem "http_accept_language"
gem "jquery-atwho-rails"
gem "rails-i18n"
gem "dropzonejs-rails"
gem "twemoji"

# OAuth Provider
gem "doorkeeper"
gem "doorkeeper-i18n"

gem "bulk_insert"

# 上传组件
gem "carrierwave"
# Aliyun / Upyun 可选项
gem "carrierwave-aliyun"
gem "carrierwave-upyun"
# Lazy load
gem "mini_magick", require: false

# 验证码，头像
gem "letter_avatar"
gem "rucaptcha"

# 用户系统
gem "devise"
gem "devise-encryptable"

# 通知系统
gem "notifications"
gem "ruby-push-notifications"

# 赞、关注、收藏、屏蔽等功能的数据结构
gem "action-store"

# 分页
gem "kaminari"

# 搜索
gem "elasticsearch-model"
gem "elasticsearch-rails"

# 三方平台 OAuth 验证登陆
gem "omniauth"
gem "omniauth-github"
gem "omniauth-yoyow"

# Permission
gem "cancancan"

# Redis
gem "hiredis"
gem "redis", "~> 3.3"
gem "redis-namespace"
gem "redis-objects", "~> 1.3.1"

# Cache
gem "second_level_cache"

# Setting
gem "rails-settings-cached"

# HTML Pipeline
gem "auto-space"
gem "html-pipeline"
gem "html-pipeline-rouge_filter"
gem "redcarpet"

# 队列
gem "sidekiq"
gem "sidekiq-scheduler"

# 分享功能
gem "social-share-button"

# Mailer Service
gem "postmark"
gem "postmark-rails"

gem "dalli"

gem "puma"

# API cors
gem "rack-cors", require: "rack/cors"
gem "rack-utf8_sanitizer"

gem "exception-track"
gem "status-page"

gem "bundler-audit", require: false

# Homeland Plugins
gem "homeland-jobs", "~> 0.3.0"
gem "homeland-note", "~> 0.2.0"
gem "homeland-press", "~> 0.4.0", path: './vendor/gems/homeland-press'
gem "homeland-site",  "~> 0.2.0", path: './vendor/gems/homeland-site'
gem "homeland-wiki", "~> 0.4.0"

gem "sdoc", "~> 1.0.0.rc3"

gem "bootsnap"
gem 'rest-client'

group :development do
  gem "derailed"
  # Better Errors
  gem "better_errors"
  gem "spring"
  gem "spring-commands-rspec"
end

group :development, :test do
  gem "capybara"
  gem "database_cleaner"
  gem "factory_bot_rails"
  gem "letter_opener"
  gem "listen"
  gem "rspec-rails"
  gem "rubocop", ">= 0.49.0", require: false
  gem "yard", ">= 0.9.11"

  gem "codecov", require: false
end