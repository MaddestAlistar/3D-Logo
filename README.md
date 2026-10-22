# 良哥看未来 · 3D Logo 交互官网

保留原版 **「良哥看未来」** 人物、熊猫与红黑白配色的互动徽章展示页。

## 🌐 访问

- **GitHub 仓库：** https://github.com/MaddestAlistar/3D-Logo
- **GitHub Pages 预期地址：** https://maddestalistar.github.io/3D-Logo/

> Pages 必须先在仓库 **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save** 启用，才能通过预期地址打开。

## ✨ 功能

- 鼠标拖动 / 手机触摸旋转 3D Logo
- Logo 点击激活 / 关闭发光能量模式
- 自动旋转开关、重置视角、桌面滚轮缩放
- 手机 / 平板 / 电脑自适应版式
- **小红书主页：** https://xhslink.cn/o/8SW6tCkrHad
- **TG 频道：** https://t.me/liangyouuniversity

## 📁 目录

| 文件 | 用途 |
| --- | --- |
| `index.html` | 首页；可用 GitHub Pages 直接访问 |
| `assets/logo.png` | 原交互版使用的 1024×1024 高清 Logo 透明纹理 |
| `models/LiangGe_Logo_Spline_Import.glb` | 可导入 Spline 的立体徽章 GLB（同款纹理） |
| `assets/xiaohongshu-card.svg` | 小红书跳转卡片素材 |
| `assets/telegram-card.svg` | TG 频道卡片素材 |
| `standalone.html` | 单文件离线交互版，Logo 纹理内嵌 |
| `README.md` | 本说明 |

## 使用

1. **网页访问：** 启用 GitHub Pages 后直接访问上方网页。
2. **本地下载：** 只需下载 `standalone.html`，用 Chrome / Edge / Safari 打开即可体验。
3. **Spline 编辑：** 在 https://app.spline.design/ 导入 `models/LiangGe_Logo_Spline_Import.glb`，自行设定 Hover / Click 事件、发光材质与两个外链。GLB 是静态模型文件，并不包含 HTML 的鼠标事件或外链，也不是原生 `.spline` 工程。

**技术说明：** 网页使用 CSS 3D 多层纹理形成 2.5D 视觉厚度，Spline 模型为有厚度的纹理徽章；两者都不是人物与熊猫逐件建模的完全三维雕塑。

© 良哥看未来
