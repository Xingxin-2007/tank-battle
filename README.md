# 坦克大战 · Tank Battle

一个纯 HTML/CSS/JavaScript 实现的经典坦克大战（Battle City）风格游戏，无需任何依赖，双击 `index.html` 即可在浏览器中游玩。

## ✨ 特性

- 🎮 经典玩法：控制坦克移动、开火，摧毁敌方坦克并保卫基地
- 🧱 四种地形：砖墙（可破坏）、钢铁（普通炮弹无法摧毁）、河流（阻挡坦克）、树林（遮挡视野）
- 💥 敌人生成与 AI：每关敌人递增，自动寻路并开火
- ⭐ 能量补给：生命、护盾、加速、全屏清场
- 🎵 音效：基于 Web Audio API 的射击 / 爆炸 / 拾取音效
- 📱 响应式界面，键盘操作，含暂停、计分、关卡系统

## 🕹 操作

| 按键 | 动作 |
| --- | --- |
| `↑` `↓` `←` `→` 或 `W A S D` | 移动 |
| `空格` 或 `J` | 开火 |
| `P` | 暂停 / 继续 |
| `Enter` | 开始 / 重新开始 |

## 🚀 运行方式

### 本地直接打开

直接双击 `index.html`，或在命令行中：

```bash
# 使用任意静态服务器，例如 Python
python -m http.server 8000
# 然后访问 http://localhost:8000
```

### 在线游玩（GitHub Pages）

仓库启用 GitHub Pages 后，即可通过 `https://<用户名>.github.io/<仓库名>/` 在线游玩。

## 📁 项目结构

```
tank-battle/
├── index.html   # 游戏全部代码（HTML + CSS + JS）
└── README.md    # 说明文档
```

## 📄 License

MIT
