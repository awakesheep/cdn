部署指令

```
# 将更改提交
git add .
git commit -m "npm publish"
# 更新package版本号
npm version patch
# 推送至github触发action
git push
```

[jsdelivr浏览](https://cdn.jsdelivr.net/npm/xue-hy-cdn/)

[unpkg.zhimg预览](https://unpkg.zhimg.com/xue-hy-cdn@1.0.0/)

  if theme.categoryBar.enable

   \#categoryBarContainer.recent-post-item(style = 'height:auto;width:100%; padding :0px;')

​    \#categoryBar!= list_categories(site.categories,{class: 'categoryBar', depth: 1})