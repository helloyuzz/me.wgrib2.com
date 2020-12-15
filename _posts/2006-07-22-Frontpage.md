---
title: '迁移至Jekyllrb Frontpage'
---
   
从微软博客迁移至本站Jekyllrb，免费了，只是可惜之前写了很多的内容，但迁移的时候不知道怎么删了，哎~~很可惜，真的是写了好多好多的东西啊！

1、Jekyll Frontpage  
```
<div class="mermaid">
流程图：mermaid（graph LR;） 
</div>
```
  
2、Ruby
```
gem install jekyll bundler
gem install bundler jekyll
bundle install 
bundle exec jekyll serve
```

3、Setup：  
```
[x] RubyInstaller
https://rubyinstaller.org/downloads/

[x] Jekyll
gem install jekyll bundler
jekyll -v

[x] gem sources
gem -v
gem sources --add https://gems.ruby-china.com/
gem sources --remove https://rubygems.org/
gem sources -l

[x] Install gems - 国内ruby-china.com镜像服务器
bundle install

[x] Run Application
bundle exec jekyll serve
```

4、Emojo参考:point_right:
```
https://www.webfx.com/tools/emoji-cheat-sheet/
```
