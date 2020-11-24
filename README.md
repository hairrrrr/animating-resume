# 一个会动的简历模板

> This is my resume

[预览](https://www.cctechblog.cn/animating-resume/public/)

## 使用方法

``` bash
git clone git@github.com:jirengu-inc/animating-resume.git // 可以先 fork 然后 git clone 自己的仓库
cd animating-resume
npm install
npm run dev // 这一步可以跳过
```

## 部署方法


1. 编辑 config/index.js，修改第 10 行的 assetsPublicPath，值为 `项目名/dist`。如果你没有修改项目名 animating-resume，则可跳过此步骤。

2. 编译、上传
    ``` bash
    npm run build
    git add .
    git commit -m "update"
    git push
    ```

3. 开启 GitHub Pages 功能


## 撰写你的简历

修改：

- src/App.vue   
- src/Mobile.vue

两个都要修改，手机和电脑对应不同的格式

