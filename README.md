> 项目思考阶段
## 项目来源
>chrome 的性能审核 coverage计算再加一些自动化模拟测试，应该可以捣鼓出来一个覆盖网站上所有代码的可用性是否可用的，这样的话，在build 时候，就可以减少大量无效代码。


## 知识数理
### 
### Chrome Covarage 可以计算当前页面被用了多少css、js
> 只能是当前的页面展示，其他页面需要点开才会被计算在内。主要用于延迟加载非关键脚本
### webpack
### 前端一些模拟用户的事件
## 自动化测试/单元测试
## 覆盖Coverage 
### css伪类 模拟人工操作
> 详细表格 http://www.w3school.com.cn/cssref/css_selectors.asp
- 链接
    - link
    - visited
    - hover
    - focus
    - active
    - focus-within

- before
- after
- enabled
- disabled
- checked
- not(selector)

> 以css 为基准，可以在若干次计算后，去判断某些伪类是没有该功能
### js事件 
- onload
- onfocus


- 鼠标事件
    - onabort
    - onblur
    - onchange
    - onclick
    - ondbclick
    - onerror
    - onfocus
    - onkeydown
    - onkeypress
    - onkeyup
    - onload
    - onmousedown
    - onmousemove
    - onmouseout
    - onmousecover
    - onmouseup
    - onreset
    - onresize
    - onselect
    - onsubmit
    - onunload
## 流程计算

## 拓展额外的思考(和以上想法有些冲突之处)

> 一些网站可以把全部的网站文件除了异步的接口请求，都可以打包在一个文件中，这样的话就是一个app了
