- 桌面小组件
- （我真不知道怎么取名字😂）
- 一个集实时信息显示与音乐控制于一体的桌面悬浮窗工具

## 🌟 功能特性

- **实时信息显示**
  - 当前时间与日期
  - 天气查询（支持全球城市）
  - CPU/内存使用率监控
  - 网络流量统计
  - 动态CPU使用率折线图
  - 随机个性签名

- **音乐控制**
  - 本地音乐文件夹选择
  - 播放/暂停控制
  - 切歌（上一曲/下一曲）
  - 快进/快退30秒
  - 播放进度显示
  - 历史播放记录保存

- **交互特性**
  - 右键菜单控制（位置锁定/作者信息/退出）
  - 窗口透明度调节
  - 自动窗口置底吸附
  - 窗口位置记忆功能

## 📥 安装与运行

### 依赖安装
  -  pip install pygame requests psutil matplotlib
  -  首次运行会自动生成location.txt
  -  在文件中输入城市英文名（如beijing或london）
  -  保存后重启程序

## 🎮 使用指南
### 基本操作
 - 右键菜单：窗口锁定/解锁、查看作者信息
 - 左键移动：移动窗口位置（未锁定时）
 - 天气点击：强制刷新数据

### 音乐控制
- </>：切换曲目
- <</>>：30秒跳转
- ▲/■：播放/暂停
- "选音乐"按钮：选择音乐文件夹

## ⚠️ 注意事项
### 天气服务
- 使用wttr.in API
- 部分天气描述需手动汉化
- "无服务"表示API暂时不可用

### 音乐播放
- 支持格式：mp3/wav/aac/flac/ogg/m4a
- 已知pygame播放进度控制存在限制
- 切换曲目时可能有1秒延迟

### 其他
- 窗口默认透明度70%
- 位置信息保存在pos.txt
- 音乐记录存储在music.txt

## 🛠️ 技术栈
- 界面框架：tkinter
- 音频处理：pygame
- 系统监控：psutil
- 数据可视化：matplotlib
- 网络请求：requests

## 📝 待优化项
- 完善异常处理机制
- 优化资源占用
- 增加天气图标支持
- 改进播放进度控制
- 添加主题切换功能

## 📧 联系作者
- 华子（Yauhak）
- QQ: 3953814837
- ✉️ 欢迎提交issue或通过QQ交流建议

# "代码写于2025.4，保留所有解释权"
