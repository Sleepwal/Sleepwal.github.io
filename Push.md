添加新文章
```sh
# 在当前 根目录 下输入
hugo new posts/hello-hugo.md
```

提交
```sh
# 进入 public/ 目录并初始化 Git
git checkout -b gh-pages

# 提交构建结果并推送到 gh-pages 分支
git add .
git commit -m "手动部署 Hugo 页面"
git push -f origin gh-pages
```
