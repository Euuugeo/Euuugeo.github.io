# 谌乐俊杰的个人主页

基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 构建的个人学术主页，计划部署至：

<https://Euuugeo.github.io>

## 内容

- 个人简介与研究兴趣
- 教育经历
- 科研及工程项目
- 荣誉与竞赛
- Markdown 版简历

## 本地预览

项目使用 Jekyll。安装 Ruby、Bundler 和依赖后运行：

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

然后访问 <http://localhost:4000>。

也可以使用 Docker：

```bash
docker compose up
```

## 更新内容

- 站点基本信息：`_config.yml`
- 顶部导航：`_data/navigation.yml`
- 首页：`_pages/about.md`
- 简历：`_pages/cv.md`
- 荣誉：`_pages/awards.md`
- 项目：`_portfolio/`

## 隐私

公开站点不包含简历中的手机号、生日、政治面貌等敏感字段。提交变更前请再次检查新增文件是否适合公开。
