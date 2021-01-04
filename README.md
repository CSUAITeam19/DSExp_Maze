# DSExp_Maze

数据结构实验: 基于搜索技术的迷宫寻路系统

包含三个子模块:

- [MazeAlgorithm](MazeAlgorithm\README.md)
  - 生成迷宫
  - 判定迷宫
  - 使用搜索算法生成搜索数据

- [MazeEditor](MazeEditor\README.md)
  - 可视化编辑迷宫
  - 调用相应算法
  - 向MazeViewer发送更新信号
  - 向Minecraft服务器发送迷宫数据和路径信息, 
- [MazeViewer](MazeViewer\README.md)
  - 读取迷宫数据, 以3D模型的形式展现
  - 根据搜索数据, 播放算法搜索过程
  - 监听更新信号, 自动更新迷宫和搜索数据