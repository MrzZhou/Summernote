# Summernote

Super simple WYSIWYG Editor.

[![Build Status](https://travis-ci.org/summernote/summernote.svg?branch=develop)](http://travis-ci.org/summernote/summernote)
[![npm version](https://badge.fury.io/js/summernote.svg)](http://badge.fury.io/js/summernote)
[![Dependency Status](https://gemnasium.com/summernote/summernote.svg)](https://gemnasium.com/summernote/summernote)
[![Coverage Status](https://coveralls.io/repos/summernote/summernote/badge.svg?branch=develop&service=github)](https://coveralls.io/github/summernote/summernote?branch=develop)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/summernoteis.svg)](https://saucelabs.com/u/summernoteis)

### 页面引入部分Summernote

Summernote是一款基于bootstrap的富文本编辑器, 使用简洁且方便, 使用方法很简单, 首先需要将项目下载到您的静态资源中, 其次在您的HTML文件中仅需要引入4个文件, 如下所示:

```html
<link rel="stylesheet" href="/static/summernote/dist/bootstrap.css">
<link rel="stylesheet" href="/static/summernote/dist/summernote.css">
<script src="/static/summernote/dist/summernote.js">
<script src="/static/summernote/dist/bootstrap.js">
```

### 元素标签部分

Summernote编辑器在页面的引用同样非常简单, 您只需要这样做即可:

```html
<textarea id="content" name="content"></textarea>
```

您可以使用任何的标签, 例如textarea, div, p等等, 但是如果你需要用form表单简单的将数据传到后端去的话, 你就得使用textarea, 因为只有textarea赋name名是有效的.



### 初始化

Summernote初始化只需要在页面底部写入一段JavaScript代码即可:

```html
<script>
	$(document).ready(function() {
    	$('#content').summernote();
    });
</script>
```

