# Card Battle Game

一款使用 Godot 引擎开发的卡牌对战游戏，支持自定义卡牌和在线联机对战。

## 项目特性

- 🎴 **自定义卡牌系统** - 灵活的卡牌设计和自定义机制
- 🎮 **Godot 引擎** - 基于开源 Godot 游戏引擎
- 🌐 **联机对战** - 支持网络多人实时对战
- ⚡ **轻量级设计** - 高效的网络同步和游戏逻辑

## 快速开始

### 系统需求

- Godot 4.0 或更高版本
- 支持 Windows、macOS、Linux 平台

### 安装与运行

1. 克隆仓库
```bash
git clone https://github.com/wangwanwang6/card-battle-game.git
cd card-battle-game
```

2. 用 Godot 编辑器打开项目
```bash
godot project.godot
```

3. 运行游戏
   - 在 Godot 编辑器中按 F5 或点击 "运行项目" 按钮

## 项目结构

```
card-battle-game/
├── assets/              # 游戏资源（图片、音频等）
├── scenes/              # Godot 场景文件
├── scripts/             # GDScript 脚本
│   ├── card/           # 卡牌相关逻辑
│   ├── battle/         # 对战系统
│   ├── network/        # 网络联机功能
│   └── ui/             # 用户界面
├── project.godot       # Godot 项目配置文件
└── README.md
```

## 游戏系统设计

### 卡牌系统
- 卡牌属性定义与管理
- 自定义卡牌效果和技能
- 卡牌数据持久化

### 对战系统
- 回合制对战逻辑
- 玩家操作与交互
- 战斗流程管理

### 网络系统
- 玩家连接与匹配
- 实时数据同步
- 网络延迟处理

## 开发规划

- [ ] 核心卡牌数据结构
- [ ] 基础对战场景与UI
- [ ] 卡牌编辑器工具
- [ ] 网络同步系统
- [ ] 玩家账户系统
- [ ] 卡组构建系统
- [ ] AI 对手（可选）

## 贡献

欢迎提交 Issue 和 Pull Request！

## 许可证

待定

## 联系方式

- GitHub: [@wangwanwang6](https://github.com/wangwanwang6)
