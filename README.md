# 关于 #

本仓库用于记录学习 [Ruby on Rails Guides (v3.2.8)](http://guides.rubyonrails.org/index.html)

# 操作记录 #

2012-10-12

[Getting Started with Rails](http://guides.rubyonrails.org/getting_started.html)

3.2 Creating the Blog Application

	$ rails new blog --skip-bundle
	$ cd blog

编辑 Gemfile 

查找：

	source 'https://rubygems.org'

替换为：

	source 'http://ruby.taobao.org'

接着在文件最后插入一行

	gem 'therubyracer'

保存并退出文件

	$ bundel install

3.4 Creating the Database

	$ rake db:create

4.1 Starting up the Web Server

	$ rails server

4.2 Say “Hello”, Rails

	$ rails generate controller home index

在 http://guides.railschina.org/getting_started.html 7.2 Rails 说 Hello" 这部分有出入，搞得我根本就找不到 `app/views/home/index.html.erb`
