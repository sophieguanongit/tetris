---
name: tetris
description: "经典俄罗斯方块游戏，单机版，浏览器直接玩。支持得分、等级加速、下一个预览。【当用户说'玩俄罗斯方块'、'来一局方块'、'tetris'、'打方块'时使用】"
metadata:
  openclaw:
    emoji: "🎮"
---

# Tetris Skill

经典俄罗斯方块，单文件 HTML 游戏，浏览器打开即玩。

## 调用方式

将游戏 HTML 复制到输出目录并用浏览器打开：

```bash
mkdir -p /data/html-ai/tetris && cp /root/.openclaw/skills/tetris/tetris.html /data/html-ai/tetris/tetris.html && open /data/html-ai/tetris/tetris.html
```

宿主机路径：`C:\Users\admin\Desktop\AI HTML\tetris\tetris.html`

## 游戏操作

| 按键 | 功能 |
|------|------|
| ← → | 左右移动 |
| ↑ | 旋转 |
| ↓ | 软降（+1分） |
| Space | 硬降（+2分/格） |
| P | 暂停/继续 |
| R | 游戏结束后重新开始 |

## 游戏规则

- 经典 7 种方块（I O T S Z J L）
- 消 1/2/3/4 行分别得 100/300/500/800 × 等级
- 每消 10 行升一级，下落速度递增
- 方块堆到顶部游戏结束

## 输出

在浏览器中打开游戏页面，用户直接用键盘操作。
