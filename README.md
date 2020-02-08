# Zombie-Game
## Game Engine: Unity 2018.4.6f1
## Game Source Code: https://drive.google.com/file/d/1GeVT0hFBIkkR_tkZ-sYO0BMYB2zZEm9v/view?usp=sharing
## Game Download: https://drive.google.com/file/d/1YBUGAkNdn4z3VU0gxmX9NSqSmdqGvDVT/view?usp=sharing
## Demo Video: https://www.youtube.com/watch?v=4mIdjkdrzdw

### 關卡設計:
設計了兩個關卡，第一關是近戰敵人，第二關是遠戰敵人。場景是利用免費素材搭建，有障礙物，跳上去可以躲開敵人的攻擊。
### 遊戲玩法:
玩家是一名有人類意識的殭屍，卻被人類瘋狂追殺，他需要自救，要對人類作出反擊…
#### a. 操作:


⚫ 角色移動: WASD 八方位移動


⚫ 鏡頭移動: 滑鼠移動


⚫ 玩家攻擊: 滑鼠左鍵，可以噴出液體射向人類。


#### b. 勝利條件: 每關擊殺 10 個殘暴的人類


### 1.
a. 近戰敵人是使用棒球棍的市民，會追蹤玩家，到了攻擊範圍就會攻擊。


b. 遠戰敵人是使用槍的警察，會追蹤玩家，到了攻擊範圍就會攻擊。


### 2.
a. 血量條: 敵人和玩家都有血量條，敵人的血量條要跟著鏡頭移動。


b. 擊殺數: 左上角會顯示擊殺敵人的數目。


c. Slider(遊戲中按 ESC): 可以調整角色移動速度


d. Dropdown(遊戲中按 ESC): 調整難度:


⚫ Easy: 5 秒生一個敵人


⚫ Normal: 2.5 秒生一個敵人


⚫ Hard: 1 秒生一個敵人


### 3.
因為使用 DontDestroyOnLoad 的 API，所以放著背景音樂的物件，不會因為轉場景而 Destroy
