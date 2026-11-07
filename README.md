# 嘉文的个人作品集

粉金色黄昏湖面、Three.js 粒子 J、衬线大标题与六个作品。单个 `index.html` 包含内联 CSS 和一个 ES-module 脚本，无需构建。

## 本地预览

```sh
python3 -m http.server 8080
```

打开 http://localhost:8080 。Three.js 和字体通过 CDN 加载；加载失败时使用静态渐变背景，作品与导航仍可使用。

包括桌面和手机布局、项目分类、作品详情、GitHub 链接、声音与动画开关、键盘导航和减少动态效果支持。环境声音默认关闭。

图片来自相应项目的实际界面或游戏画面。视觉参考用户提供的 Kinova 动态网站提示词，场景用 Three.js 实时生成；项目截图使用本地图片资源。

部署：GitHub Pages，仓库 `oyjw140814.github.io`，`main` 分支根目录。

`assets/projects/` 为优化后的 WebP 截图；本机的聊天盘点文档、开发缓存和发布工作区不纳入公开仓库。
