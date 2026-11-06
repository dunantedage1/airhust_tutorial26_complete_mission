# airhust_tutorial26_complete_mission

第五关（综合任务）的地图包和任务书。

```
第五关任务书.pdf / .tex     任务书（xelatex + ctex 编译）
板块五.md                   板块五的说明页（骨架）
src/airhust_complete_mission   Gazebo 地图包：launch、worlds、models、随机布置节点
```

跑之前把 `src/` 放进 catkin 工作空间，`catkin_make` 之后：

```bash
roslaunch airhust_complete_mission mission.launch
```

地图长 17m、宽 8m，每次启动会随机重排柱子、门、方环、二维码和三张图片，具体规则见任务书。
