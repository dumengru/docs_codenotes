# docs_codenote
量化交易相关代码笔记

1. 修改_config.yml
- title: 显示在浏览器url栏
- timezone: Asia/Shanghai

2. 修改index.md, 这是网站首页, 在菜单栏第一栏

3. _posts文件内容在菜单栏最底部(Change Log)
- 文件名称以日期开头, 会自动解析

4. 修改changelog.html第一个标签

5. _docs文件排序
- 首先按照内部文件夹顺序排序
- 之后按照文件标题的order排序

6. 若文件格式不对, 上传后无法刷新GitHub Page


### website
1. "Gemfile"中添加`gem 'tzinfo-data'`
2. 添加标准目录: categroy
3. 到google maps platform 获取apikey, 然后添加到"_config.yml"中`google_maps_javascript_api_key`
3. 执行`bundle add webrick`
4. 启动`bundle exec jekyll serve`

### discussion

```html

<script src="https://giscus.app/client.js"
        data-repo="dumengru/dumengru.github.io"
        data-repo-id="R_kgDOIj5srQ"
        data-category="General"
        data-category-id="DIC_kwDOIj5src4CS83P"
        data-mapping="og:title"
        data-strict="1"
        data-reactions-enabled="1"
        data-emit-metadata="1"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>
```
