# UE5-demo
This is a Unreal Engine5 demo, which named castaway, in this folder.
1.游戏规则说明
这是一个第三人称游戏，主角Lary流落到了一个荒岛上，周围是一望无际的海洋，他必须在小岛上寻找食物和水源维持健康，等待救援。
游戏中设置了四个进度条（0-100）来表征当前状态，分别是健康值，饥饿，口渴，救援。游戏开始时，健康值，饥饿，口渴进度条都显示100，救援显示0。随着时间的推移，每隔2s饥饿值下降20，每隔5s口渴值下降10，当饥饿值或者口渴值下降为0时，健康值下降20，饥饿值或者口渴值重置为100；每隔5s救援值增加2。若健康值下降为0，则游戏失败；若救援值达到100，则游戏胜利。
在小岛上，随机散落着55颗椰子，可以作为食物；并且有一处淡水水源。当食用一颗椰子后，饥饿值增加50；当饮用一次淡水后，口渴值增加30。
2.演示视频说明
在演示用mp4视频中，我展示了游戏中的主要功能和场景，并且用序号来分隔表示，以下是每个序号后片段的展示说明。
0-游戏开始界面，点击“start”按钮，开始游戏
1-当Lary靠近淡水水源时，表示饮用了淡水，口渴值增加
2-当Lary碰撞到椰子后，表示食用了椰子，饥饿值增加
3-椰树林场景
4-为礁石添加了碰撞体
5-海洋流体景观
6-游戏胜利界面，按“once again”再来一次
7-游戏失败界面，按“once again”再来一次
8-游戏开始界面，按“quit”退出游戏
9-游戏胜利界面，按“quit”退出游戏
10-游戏失败界面，按“quit”退出游戏
3.技术说明
本游戏使用Unreal Engine 5.2.1开发。主要使用了以下技术：Fluid Flux流体插件，UIWS交互水体插件，Niagara特效，碰撞体添加，IK重定向，UMG，HUD
4.关于打包
由于近期使用Android Studio的时候，调整了部分配置，导致UE5的打包出现问题，暂不能提供打包文件。
