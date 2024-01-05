# ProjectV
### V计划：不断迭代的 *家庭服务器+家庭数据监控+家庭自动化+智能家居+家庭人工智能管家+下载服务监管* 管理系统

- 服务组大版本使用V开头+字母表示，如第一个大版本为VA，第二个大版本为VB，以此类推
- 体系中每个开源组件可能在不同应用场景和不同V计划版本中使用
- 总体来说本项目体系更像是一个分布式系统，并且开发者希望这个项目能够有较高的可用性、可拓展性、可移植性
- 本项目遵循Apache License 2.0协议，欢迎大家提出建议，欢迎大家使用本项目体系中的组件，也欢迎大家使用本项目体系中的组件开发自己的项目

### 2023-06-18 VA-极简轻控
- 总览
    <details><summary>架构图</summary></details>

- 系统体系 
  - [x] 钉钉服务器监控：[ServerWatcher-DingBot-Go](https://github.com/tyza66/ServerWatcher-DingBot-Go)
  - [ ] 服务器状态可视化：[ServerWatcher-Center](https://github.com/tyza66/ServerWatcher-Center)
  - [x] 文件管理：[VA-File](https://github.com/tyza66/VA-File)
  - [x] 智能中控：[HomeHolder-DingBot](https://github.com/tyza66/HomeHolder-DingBot)
  - [x] 内网穿透：[Sakura Frp](https://www.natfrp.com/)
  - [x] 自动化脚本：[qinglong](https://github.com/whyour/qinglong)
  - [x] 容器化：[Docker](https://www.docker.com/)
  - [x] 数据库：[MySql](https://www.mysql.com/)  
  - [x] 绿植管理：[GreenBelt](https://github.com/tyza66/GreenBelt)
  - [x] 家庭记账: [IHaveAccountAtHome](https://github.com/tyza66/IHaveAccountAtHome)
  - [ ] 模型训练管理：AlchemyFurnace 
  - [ ] 摄像头人脸识别：TheEyesOfTheFamily 
  - [x] 订阅信息推送：[DailySub-DingBot](https://github.com/tyza66/DailySub-DingBot)  
  - [x] ChatGPT钉钉机器人：[ChatGPT-DingBot](https://github.com/tyza66/ChatGPT-DingBot)  
  - [x] 文心一言钉钉机器人：[ERNIE-DingBot](https://github.com/tyza66/ERNIE-DingBot)  

By：tyza66