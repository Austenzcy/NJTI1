# NJTI 第二版网站

这是 NJTI 南京大学专属校园人格测试的第二版静态网站。

## 文件说明

- `index.html`：网站入口，必须放在仓库根目录。
- `style.css`：页面样式，已适配电脑端和手机端。
- `script.js`：答题、计分、语言切换、结果图表逻辑。
- `data.js`：第二版题库、人格文案、多语言文本。
- `assets/results/`：16 张人格结果图，已由用户提供的 PNG 压缩成 WebP，用于网页加载。
- `assets/common/logo.svg`：网站小图标。

## 第二版更新内容

1. 使用第二版 Word 文档作为文字基准。
2. 替换为用户提供的 16 张新人格图。
3. 首页增加语言选择：
   - 中文
   - English
   - Français
   - العربية
   - Русский
4. 首页增加作者署名：Austen。
5. 结果页增加四维度百分比图表。
6. 题目页不显示维度标签，只显示题目和选项。
7. 页面以简体中文为默认语言，其他语言可切换。
8. 阿拉伯语支持从右到左阅读方向。

## 上传 GitHub Pages 的方法

把本文件夹里的所有内容直接放到 GitHub 仓库根目录，确保 `index.html` 在最外层。

正确结构示例：

```text
zcy-s_pub/
├─ index.html
├─ style.css
├─ script.js
├─ data.js
├─ README_使用说明.md
└─ assets/
```

然后在 GitHub 仓库里打开：

`Settings → Pages → Deploy from a branch → main / (root) → Save`

等待 1 到 3 分钟后访问网站链接。
