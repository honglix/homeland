# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }

gem "jbuilder"
gem "rails"
gem "rails_autolink"
gem "sass-rails"
gem "turbolinks"
gem "uglifier"
gem "webpacker", "~> 5.x"

gem "view_component", require: "view_component/engine"

gem "pg"

gem "devise"
gem "devise-encryptable"
gem "cancancan"
gem "doorkeeper"
gem "doorkeeper-i18n"
gem "omniauth"
gem "omniauth-github"
gem "omniauth-twitter"
gem "omniauth-wechat-oauth2"
gem "omniauth-rails_csrf_protection"

gem "jieba-rb"
gem "dotenv-rails"

gem "rack-attack"
gem "http_accept_language"
gem "rails-i18n"
gem "twemoji"

# Uploader
gem "carrierwave"
# Aliyun / Upyun / Qiniu
gem "carrierwave-aliyun"
gem "carrierwave-upyun"
gem "carrierwave-qiniu"
gem "qiniu"

gem "mini_magick", require: false

# Captcha
gem "rucaptcha"
gem "recaptcha"

# Notification
gem "notifications"
gem "ruby-push-notifications"

gem "action-store"

gem "kaminari"
gem "form-select"
gem "enumize"

gem "pghero"
gem "exception-track"

# Cache
gem "redis"
gem "redis-namespace", github: "resque/redis-namespace"
gem "second_level_cache"

# Setting
gem "rails-settings-cached"

# HTML Pipeline
gem "auto-correct"
gem "html-pipeline"
gem "html-pipeline-auto-correct"
gem "redcarpet"
gem "rouge"

gem "sidekiq"
gem "sidekiq-cron"

gem "social-share-button"

# Mailer Service
gem "postmark"
gem "postmark-rails"

gem "puma"

# API cors
gem "rack-cors", require: "rack/cors"

gem "bootsnap"

gem "puma_worker_killer"
gem "nokogiri", ">= 1.11.0.rc4"

group :development do
  gem "spring"
  gem "byebug"
  gem "letter_opener"
  gem "derailed_benchmarks"
end

group :development, :test do
  gem "listen"

  gem "mocha"
  gem "minitest-spec-rails"
  gem "factory_bot_rails"

  gem "rubocop", require: false
end
