# DemoBlog
WEB组第一次练习 -> 简单的博客系统


# 简单入门
=============
## >> 环境配置
-------------
### *Nix：

	1. 配置PHP5.x(大于5.6)
	2. 配置composer : http://getcomposer.org
	3. 项目下载到本地 : git clone

### Windows:
	= = 待补充
	

## >>入门教程
-------------

1. 官方教程翻译 : http://www.golaravel.com/laravel/docs/5.0/
2. 一篇不错的Laravel中文教程 : https://lvwenhan.com/laravel/432.html
	

### 已有的资源:

1. 静态页面半成品 : /views文件夹
2. 框架本体 : /laravel
3. 数据表文件 ： /sqlDumps


### 数据表结构:
	Article:
		->id  (主键)
		->name    (文章标题)
		->content 	(内容)	
		->sort_id	(分类表外键)
		->update_time	(Laravel管理)
		->create_time	（Laravel管理）
	Sort:
		->id	(主键)
		->name	(名称)
		
### 要求:

 Fork到自己的仓库里，在两周内完成。
