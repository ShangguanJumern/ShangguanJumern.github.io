source 'https://mirrors.huaweicloud.com/rubygems/'  # 华为云 RubyGems 镜像源

# 管理 Jekyll 版本的主入口
# 需要变更版本时，修改下方版本号后保存文件并运行：
# 
#     bundle install
# 
# 运行 Jekyll 时请使用：
#
#     bundle exec jekyll serve
#
# 这能确保使用正确的 Jekyll 版本
gem "jekyll", "~> 4.3.4"
# 这是 Jekyll 的默认主题，可替换为任意你喜欢的主题
gem "minima", "~> 2.5"
# 如需使用 GitHub Pages，请删除上方的 gem "jekyll"
# 并取消注释下方这行。更新时请运行 bundle update github-pages
# gem "github-pages", group: :jekyll_plugins
# 在此处添加你的插件
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-spaceship'
end

# Windows 和 JRuby 平台需要时区数据支持
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
