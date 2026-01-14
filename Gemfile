# frozen_string_literal: true

source "https://rubygems.org"

group :jekyll_plugins do
  gem "jekyll-polyglot"  # ← これが必須です
  gem "jekyll-sitemap"
  # 他のプラグイン...
end

gem "jekyll-theme-chirpy", "~> 7.4", ">= 7.4.1"

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
