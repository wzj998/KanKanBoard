# Mobile Kanban MVP (Android-first, future cross-platform)

## 目标
构建一个**手机本地看板 App** 的**最小可玩原型（MVP）**：
- 先支持 **Android**。
- 未来可扩展到 **Web** 与 **iOS**。

## 最小可玩原型范围
### 1. 列（Column）管理
- 顶部或右下角提供 **“＋”** 按钮。
- 点击“＋”可以新增列（例如：`Todo`、`Doing`、`Done`）。

### 2. 列内项目（Card/Item）管理
- 在每一列中提供 **“新增项”** 按钮或输入入口。
- 允许输入文字并创建项目卡片。

### 3. 拖拽移动
- 支持将项目卡片在**不同列之间拖动**以改变状态。

## 交互流程示例
1. 打开 App，看到默认列或空白面板。
2. 点击“＋”新增列 `Todo`、`Doing`。
3. 在 `Todo` 列添加事项卡片：`写 UI`。
4. 长按卡片并拖动到 `Doing` 列。

## 技术方向建议（未来扩展）
- **本地存储**：MVP 先使用**单个本地 JSON 文件**存储。
- **跨平台规划**：
  - Android 先行（Kotlin + Jetpack Compose 或 Flutter）。
  - 未来 Web / iOS：建议优先考虑 **Flutter** 或 **React Native + Web**。

## 交付物
- 仅包含 MVP 功能的原型设计与基础交互。
- 不包含用户系统、云同步、多端协作等功能。
