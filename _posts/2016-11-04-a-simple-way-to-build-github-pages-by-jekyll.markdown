---
layout: post
title:  "A simple way to build Github Pages by Jekyll."
date:   2016-11-04 14:54:02 +0800
categories: jekyll and github pages
---

## e.g.
username = ihuixu

1.new folder.

{% highlight ruby %}
mkdir ihuixu.github.io
cd ihuixu.github.io
{% endhighlight %}

2.new jekyll program.

{% highlight ruby %}
sudo gem install jekyll bundler
jekyll new .
{% endhighlight %}

3.git push 

{% highlight ruby %}
git init
git commit -m "first commit"
git remote add origin https://github.com/ihuixu/ihuixu.github.io.git
git push -u origin master
{% endhighlight %}

## ps
1.How to start server in local.

{% highlight ruby %}
bundle install
bundle exec jekyll serve
{% endhighlight %}

2.How to change the theme of the site.

`vi Gemfile`
{% highlight ruby %}
gem 'themename'
{% endhighlight %}

`vi _config.yml`
{% highlight ruby %}
theme: themename
{% endhighlight %}

3.You may check the ruby's version, and install bundler again.

{% highlight ruby %}
ruby -v
rvm install ruby-2.2.2
{% endhighlight %}

{% highlight ruby %}
gem install jekyll bundler
bundle install
{% endhighlight %}


