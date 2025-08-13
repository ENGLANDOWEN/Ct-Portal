# frozen_string_literal: true
source "https://rubygems.org"

# 核心依赖
gem "jekyll", "~> 4.4.1"  # 指定 Jekyll 版本，与 Cloudflare 环境兼容
gem "jekyll-theme-chirpy" # 使用 fork 的主题

# 开发和测试依赖（确保安装）
gem "html-proofer", "~> 5.0"  # 用于静态内容检查
gem "nokogiri", "~> 1.18.9"  # 处理 HTML/XML，可能被间接依赖
gem "async", "~> 2.27.2"     # 异步处理，可能被主题需要
gem "pdf-reader", "~> 2.15.0" # 处理 PDF，可能被主题需要
gem "rainbow", "~> 3.1.1"    # 颜色输出，可能被间接依赖
gem "typhoeus", "~> 1.4.1"   # HTTP 请求，可能被间接依赖
gem "yell", "~> 2.2.2"       # 日志记录，可能被间接依赖
gem "zeitwerk", "~> 2.7.3"   # 自动加载，可能被间接依赖

# 平台特定依赖
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows 特定依赖
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# 指定 Ruby 版本，匹配 Cloudflare 环境
ruby "3.4.4"
