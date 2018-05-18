### Use construct 2 create many h5 games.


#### 1. 打飞机H5游戏

* 目录名称：Hit_Plane
* 游戏名称： 飞机大战简版 / hit plane h5 game
* 工具： construct 2
* 标签： 飞机、敌人、子弹、击中、爆炸、重新游戏、键盘
* 在线试玩地址：[在线打飞机H5游戏demo](https://riverscoder.github.io/construct2-h5-games/Hit_Plane/index.html) 
* 游戏简介：
    1. 键盘上下左右操控飞机移动
    2. 空格键发射子弹
    3. 敌机随机位置时间从上面进入画面
    4. 点击重新游戏


#### 2. tappy plane h5 games

* 目录名称：Tappy_Plane
* 游戏名称： 像素飞机 / tappy plane h5 games
* 工具： construct 2
* 标签： 飞机、岩壁、岩柱、击中、爆炸、重新游戏、手指触控
* 在线试玩地址：[像素飞机H5游戏demo](https://riverscoder.github.io/construct2-h5-games/Tappy_Plane/index.html) 
* 游戏简介：
    1. 手指或鼠标触控 飞机向上运动
    2. 吃星星 累计分数 统计最高分数
    3. 岩壁、岩柱碰撞 结束游戏
    4. 重新游戏


#### 3. use btn control player's motion

* 目录名称：Contorl_Motion
* 游戏名称： 人物控制 / control player's motion
* 工具： construct 2
* 标签： 运动、Platform、虚拟控制按钮
* 在线试玩地址：[虚拟玩家控制demo](https://riverscoder.github.io/construct2-h5-games/Contorl_Motion/index.html) 
* 游戏简介：通过虚拟UI按钮控制人物的左、右、跳跃运动

#### 4. jump game 

* 目录名称：Jump_Game
* 游戏名称： 跳跃游戏 / jump game
* 工具： construct 2
* 标签： 跳跃、虚拟控制、分数
* 在线试玩地址：[jump game demo](https://riverscoder.github.io/construct2-h5-games/Jump_Game/index.html) 
* 游戏简介：
    1. 尺寸 480*854
    2. 添加背景 、基础元素（岩石台、player）
    3. 添加基本的动作： 落在平台后会自动向上跳跃，跳跃时采用跳跃animation、落下时采用落下animation
    4. 添加虚拟按钮，实现在落下、弹跳的过程中，完成左右位置移动
    5. 设置全局变量minScroll，compare当前的playerY轴位置，屏幕跟随滚动 ( 修改Layout默认属性unbounded scrolling为Yes, 不然设置会失效 )
    6. 在顶部随机范围x轴、y轴位置生成石板
    7. 检测石板超出屏幕，销毁
    8. 跳出边界后，瞬间回到另个边界，实现边界互通效果
    9. 在每个石板上随机增加指定数量金币0-3个（条件循环遍历）
    10. 金币超出屏幕，销毁
    11. 拾取金币动画 增加拾取金币音乐特效
    12. 随机更换生成不同的石板（动画帧）
    13. player落下超过屏幕，游戏结束，重新游戏
