# Android Fitness & Workout Tracker

一款基于原生 Android 开发的力量训练管理与进度追踪应用，旨在帮助用户高效记录健身数据并实现可视化分析。

---

## 核心技术点

### 1. 数据持久化与架构
- **本地数据库：** 使用 **SQLite** 实现了运动数据存储，包含训练计划、动作库及历史成绩。
- **关系建模：** 建立了“训练日-动作-组数”的多级关联模型，确保数据查询的高效性与一致性。
### 2. 数据可视化 
- **自定义图表：** 开发了自定义 View 用于展示过去的训练频率与容量占比饼图。

### 3. UI设计
- **响应式布局：** 采用 **ConstraintLayout** 与 **RecyclerView**，适配不同屏幕尺寸并保证列表滑动的流畅度。
- **交互细节：** 包含便捷的滑动删除等流畅交互功能。

### 4. 自动化
- **自动化构建：** 配置了GitHub自动化工作流，在每次 Push 后自动进行版本文件生成，实现基于GitHub的静默更新及其检测。
- **版本控制：** 规范使用 Git 进行功能分支管理，保证代码迭代过程清晰可追溯。

---

## 技术栈
- **语言：** Kotlin
- **核心组件：** Jetpack (Room, ViewModel, LiveData, Navigation)
- **开发工具：** Android Studio，GitHub Actions

---

## 功能展示
<img width="345" height="615" alt="1" src="https://github.com/user-attachments/assets/f6a06086-6fca-41fe-bd66-e9fd999cd369" />
<img width="345" height="615" alt="3" src="https://github.com/user-attachments/assets/9bcae356-2ce1-451f-ba9e-ac3a15427bd3" />
<img width="345" height="615" alt="4" src="https://github.com/user-attachments/assets/751f6de0-0f5a-406b-b7c8-8647d366839c" />
<img width="345" height="615" alt="5" src="https://github.com/user-attachments/assets/815de2f8-f489-4373-8906-c0fe8e62a180" />


---

## 待办事项
- [ ] 增加动作自定义添加功能
- [ ] 增加不同的可视化图形
- [ ] 修改或添加历史记录功能
