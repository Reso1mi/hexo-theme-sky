博客效果预览：[imlgw.top](https://imlgw.top/)

fork from https://github.com/iJinxin/hexo-theme-sky

不会前端css，一些改动比较激进，所以unfork后自己维护了，感谢[@iJinxin](https://github.com/iJinxin)的贡献

## 对原主题的改动

- [x] 文章无分类和标签构建报错
- [x] 自动摘要auto_excerpt_len
- [x] 列表缩进
- [x] social_config修改为theme级别
- [x] 文章隐藏（当页不展示）
- [x] 添加分类页（基本能用）
- [x] 文章置顶 + 置顶标签 (hexo-generator-index)
- [x] 长目录加滑动条
- [x] disqus评论 & 去除gitment
- [x] 文章标题 -> 网页标题
- [x] 网页favicon自定义
- [x] 搜索页（hexo-generator-search）
- [ ] 添加Tag页
- [ ] nav重写（目前写死）
- [ ] 分页优化
- [ ] 夜间模式
- [ ] 代码重构
- [ ] 自动拉取外部文章

依赖项推荐使用
```
npm install hexo-renderer-scss-next --save
```

--- 

[线上地址](https://ijinxin.github.io/)

## 功能简介
hexo-theme-sky 是一款简洁轻量的 hexo 博客主题，主要包含以下功能：
- 语言切换，目前支持中文和英文
- 文章访问统计
- 文章目录
- 评论功能，目前使用的是gitment
- 代码高亮

## 使用指南
安装 ``` hexo ```
```
npm install hexo-cli -g
hexo init blog
```
下载 ``` hexo-theme-sky ```主题
```
cd blog
git clone https://github.com/iJinxin/hexo-theme-sky themes/sky
```
修改博客根目录下的配置文件 ```_config.yml``` , 启用 ``` sky ``` 主题
```
theme: sky
```
安装依赖项
```
npm install
npm install hexo-renderer-scss --save
```
运行
```
hexo server
```
启动服务后，访问 http://localhost:4000 预览主题

更多主题配置 [document](https://ijinxin.github.io/blog/2018/10/29/hexo-theme-sky%E6%8C%87%E5%8D%97/)

## 说明
<blockquote>
如果对您有帮助，可以点击右上角“Star”支持一下，谢谢！

或者您有更好的想法，更棒的建议，也可以提issue，我会考虑实现
<blockquote>

