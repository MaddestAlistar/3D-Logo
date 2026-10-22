# 良哥看未来 · 3D Logo 交互展示

以“良哥看未来”原创 Logo 为主体的互动展示页，保留人物、熊猫与原版红黑配色。

## 在线访问

GitHub Pages 开启后，访问：**https://maddestalistar.github.io/3D-Logo/**

> 在仓库 Settings → Pages 中将 Build and deployment 设置为 **Deploy from a branch**，Branch 选择 **main / (root)**，保存后等待 GitHub 发布。尚未启用 Pages 时上述链接可能打不开。

## 交互说明

- 鼠标拖动或手机手指拖动：旋转 Logo
- 点击 Logo：切换能量发光模式
- 自动旋转按钮：开启 / 暂停自转
- 重置视角按钮：恢复默认角度
- 滚轮：缩放 Logo（桌面端）
- 小红书：**https://xhslink.cn/o/8SW6tCkrHad**
- Telegram：**https://t.me/liangyouuniversity**

## 仓库结构

- `index.html` — GitHub Pages 首页，加载 `assets/logo.png`
- `assets/logo.png` — 从原交互版本分离出的同款高清 Logo 透明图
- `standalone.html` — 独立离线版（图片内嵌，无需同目录素材）
- `README.md` — 项目说明

## 设计和技术说明

当前网页版使用 CSS 3D 多层纹理营造立体徽章效果，并非将人物和熊猫逐一重建成完整的三维网格，也并非 Spline .spline 原生工程。需要在 Spline 编辑器中单独绑定模型点击事件和外链跳转。

© 良哥看未来
