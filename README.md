# my-music

> 音乐播放器

## chapter1

文件的组织架构重新整理

设置别名webpack.base.conf.js alias设置

加载stylus，stylus-loader的依赖加载

## chapter2

- 依赖：

babel-runtime： es语法转义

fastclick：移动端快速点击问题300毫秒延迟

babel-polyfill： es api转义

- css

@import '\~common/stylus/variable' css里面别名设置无效，加上~可以解释成模块路径，不加就是相对路径

- router

router-link tag属性 生成的标签

router-link-active 当前路由类名

