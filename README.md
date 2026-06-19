# 🌐 xiongdaa SEO - 个人主页

> 一个精美的玻璃拟态风格个人主页，包含音乐播放器、实时时钟、一言展示、歌词同步等功能。

## 📸 页面截图

### 主界面
![主界面截图](./2ad87f928b21eb6fec08319b9aa99854.png)

### 歌词面板
![歌词面板截图](./8db5affe3e23581b82d0853472f0c5e1.png)

## ✨ 功能特性

- **玻璃拟态设计** — 采用现代 Glassmorphism 风格，毛玻璃效果搭配动态背景
- **音乐播放器** — 支持 QQ 音乐、网易云音乐搜索播放，黑胶唱片动画，歌词同步显示
- **实时时钟** — 精确到秒的时间显示，带日期信息
- **一言展示** — 随机一言 + 打字机效果
- **接口日志** — 内置终端日志面板，实时查看 API 响应
- **响应式布局** — 完美适配桌面端和移动端
- **SEO 优化** — 完整的 meta 标签、sitemap、robots.txt 配置

## 🚀 快速开始

### 本地运行

```bash
# 直接用浏览器打开 index.html 即可
open index.html
```

### 部署到 GitHub Pages

```bash
# 1. Fork 本仓库
# 2. 进入 Settings > Pages
# 3. Source 选择 "Deploy from a branch"，分支选择 main，文件夹选择 /root
# 4. 保存后等待几分钟即可访问
```

### 部署到其他平台

- **Vercel**: `vercel --prod`
- **Netlify**: 拖拽整个文件夹到 Netlify Drop
- **Cloudflare Pages**: `wrangler pages deploy .`

## 📁 项目结构

```
seo/
├── index.html          # 主页面（玻璃拟态个人主页）
├── head-seo.html       # SEO Meta 标签模块
├── 404.html            # 404 页面（公益跳转）
├── robots.txt          # 搜索引擎爬虫配置
├── sitemap.xml         # 站点地图
├── README.md           # 项目说明
└── LICENSE             # MIT 开源协议
```

## 🔧 自定义配置

### 修改个人信息

编辑 `index.html`，找到以下位置修改：

| 位置 | 内容 | 示例 |
|------|------|------|
| Line ~319 | 姓名 | `xiong da` → 你的昵称 |
| Line ~326 | GitHub 链接 | `https://github.com/kssssxg` → 你的仓库 |
| Line ~331 | QQ 号码 | `YOUR_QQ_NUMBER` → 你的 QQ |
| Line ~336 | 微信号 | `YOUR_WECHAT_ID` → 你的微信 |
| Line ~341 | 邮箱 | `your.email@example.com` → 你的邮箱 |
| Line ~70 | 头像图片 | 替换 `background` URL |

### 修改背景音乐源

音乐搜索 API 配置在 `index.html` 的 `<script>` 部分：

```javascript
// QQ音乐 API
const url = `https://cyapi.top/API/qq_music.php?apikey=${CYAPI_KEY}...`;

// 网易云音乐 API
const url = `https://v2.alapi.cn/api/music/search?keyword=...`;
```

请替换为可用的 API 密钥。

## 📄 开源协议

本项目采用 **MIT License** 开源。

详见 [LICENSE](./LICENSE) 文件。

**使用时请保留作者标注**，在 HTML 页面底部已包含仓库链接标注。

## 🙏 致谢

- [Font Awesome](https://fontawesome.com/) - 图标库
- [Noto Sans SC](https://fonts.google.com/) - 中文字体
- [Hitokoto](https://hitokoto.cn/) - 一言 API
- 所有开源社区 contributors

## 📮 联系

- GitHub: [@kssssxg](https://github.com/kssssxg)
- 仓库: [xiongdaa-seo](https://github.com/kssssxg/xiongdaa-seo)

---

> ⭐ 如果觉得有用，请点个 Star 支持一下！
