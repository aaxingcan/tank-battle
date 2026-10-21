# 坦克大战 (Tank Battle)

一个用原生 **HTML5 Canvas + JavaScript** 编写的经典坦克大战（Battle City）网页小游戏。单文件即可运行，零依赖、零构建。

## 试玩

直接双击打开 `index.html`，或部署到 GitHub Pages 后访问：

```
https://aaxingcan.github.io/tank-battle/
```

## 玩法

- 控制我方坦克，击毁所有敌方坦克，并**保护底部中央的老鹰基地**不被摧毁。
- 共 5 关，每关 20 辆敌方坦克。
- 敌方坦克分为 4 种：普通、快速、火力、装甲（需 3 发才能击毁）。
- 击毁带「闪烁」标记的敌方坦克会掉落道具。

### 操作

| 按键 | 功能 |
| --- | --- |
| 方向键 / WASD | 移动 |
| 空格 / J | 开火 |
| P | 暂停 |
| M | 静音 |
| Enter | 开始 / 重新开始 |

移动端会自动显示虚拟摇杆与开火按钮。

### 道具

- ⭐ 星星：火力升级（连发 / 可击碎钢墙）
- 🛡 护盾：短暂无敌
- 💣 炸弹：消灭场上所有敌人
- ❤ 生命：+1 条命
- ❄ 冰冻：冻结敌人一段时间

### 地图元素

- 红砖墙：可被子弹摧毁
- 钢墙：普通子弹打不穿（3 级火力可摧毁）
- 河流：不可通行，子弹可穿过
- 树林：可通行，会隐藏坦克

## 技术栈

- HTML5 Canvas
- 原生 JavaScript（无依赖、无框架）
- Web Audio API（音效合成）

## 本地运行

直接用浏览器打开 `index.html` 即可，无需安装任何东西。

## 部署到 GitHub Pages

1. 进入仓库 **Settings → Pages**；
2. 将 **Source** 设为 `main` 分支、根目录 `/ (root)`，保存；
3. 稍等片刻即可通过 `https://aaxingcan.github.io/tank-battle/` 访问。

## 目录结构

```
tank-battle/
├── index.html   # 游戏（单文件，含 CSS 与 JS）
└── README.md
```

## 许可

仅供学习交流使用。
