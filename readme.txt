=== WP Disable Emoji ===
Contributors: 610216
Tags: emoji
Requires at least: 3.0
Tested up to: 4.4
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WP Disable Emoji

== Description ==

[WP Disable Emoji](http://xiedexu.cn/wp-disable-emoji.htm) | [iOpenV](http://www.iopenv.com)

Emoji 的实现方式会调用 http://s.w.org/images/core/emoji/72x72/ 下的图片来渲染 Emoji，而这个地址是国内(China)访问不了的，所以要禁用 WordPress Emoji 功能。

== Installation ==

1. 上传文件夹“wp-seo-emoji”到“/wp-content/plugins/”目录。
2. 在仪表盘插件菜单中激活该插件。

== Changelog ==

= 1.4 =

* 禁用dns-prefetch s.w.org

= 1.3 =

* 修正与后台TinyMCE编辑器ajax冲突

= 1.2 =

2016-01-20

* 修正与后台TinyMCE编辑器冲突导致TinyMCE功能图标失效bug