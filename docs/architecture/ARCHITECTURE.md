# 技术架构基线

- Unity + C#；
- PC 编辑测试，Android 首个移动目标；
- 模块化单体；
- 数据驱动配置；
- 领域逻辑与 Unity 表现层分离；
- 可注入随机种子；
- 存档带版本号与迁移入口；
- 首版不依赖生产服务器；
- 后续联机采用服务器权威原则。

初步模块：

- Core
- Characters
- Party
- Combat
- Settlement
- Technology
- Contracts
- Save
- Presentation
