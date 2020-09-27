---
title: 'Jekyllrb Frontpage'
---
Click to read more...  
   
1.Jekyll Frontpage  

Categories

<div class="mermaid">
    graph LR;
        A[https://hi.1tyu.com] -->|class| B(Life);
        A-->|class|C(Friend);
        A-->|class|D(History);
        A-->|class|E(Technology);
        A-->|class|F(Work);
        A-->|class|G(Study);
        A-->|class|H(Sports);
        B-->B1(Dailylog);
        B-->B2(Philosophy of life);
        C-->C1(WeChat);
        D-->D1(San-guo);
        E-->E1(Jekyllrb);
        H-->H1(Fishing)
</div>

  
2.Setup

```Ruby
    gem install jekyll bundler

    gem install bundler jekyll

    bundle install 

    bundle exec jekyll serve

```  
参考步骤：  
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
