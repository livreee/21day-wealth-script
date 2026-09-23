# 工银财趣 · 21天财富剧本

像素复古风（Retro Pixel）互动网页 Demo —— 工行杯参赛作品。以「21 天财富剧本」为主线，通过游戏化、任务打卡的方式向年轻用户普及理财知识。

## 在线体验

👉 GitHub Pages 地址：<https://livreee.github.io/21day-wealth-script/>

> 如首次打开提示 404，说明 Pages 刚开启、正在部署，等待约 1 分钟刷新即可。

## 项目结构

| 文件 | 说明 |
| --- | --- |
| `index.html` | 网页版 Demo 主文件（单文件、内联样式与脚本，可直接双击打开） |
| `build_retro.py` | 像素风页面/素材构建脚本 |
| `build_bgm.py` | 背景音乐（BGM）构建脚本 |
| `dl_bgm.py` | BGM 素材下载脚本 |
| `fix_attr.py` | 素材属性修正脚本 |
| `make_check.py` | 打卡/勾选状态生成脚本 |
| `make_grad_check.py` | 渐变勾选样式生成脚本 |

## 本地运行

无需构建、无需依赖，直接用浏览器打开 `index.html` 即可；或在本目录启动一个静态服务器：

```bash
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000
```

## 技术特点

- 单 HTML 文件交付，零运行时依赖，移动端自适应
- 像素点阵视觉 + 工银红品牌色 + ZCOOL 快乐体 / Press Start 2P 字体
- 任务打卡、进度状态等交互全部在前端完成
