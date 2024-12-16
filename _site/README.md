# yzhao98.github.io

brew install node
npm init
npm install


# how to run jekyll
bundle init
编辑gemfile with 
```
gem "jekyll"
gem "jekyll-paginate"
``` 

bundle install  
bundle exec jekyll serve

# 绑定域名
1. 先在域名提供商处配置 CNAME 记录：将你的自定义域名（如 y-zh.com）指向 yzhao98.github.io。
2. 在 GitHub Pages 设置中配置自定义域名：在你的仓库的 Settings 页面中设置 Custom Domain 并保存。
3. （可选）设置 A 记录：如果想让根域名（如 yourdomain.com）也指向 GitHub Pages，配置 A 记录指向 GitHub 提供的 IP 地址。
