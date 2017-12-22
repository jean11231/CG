# i5370 計算機圖學 (Computer Graphics) :computer:

:low_brightness: 此repository為計算機圖學課程所指定繳交的作業內容

## Homework 1  (Due 11/5/17) :time-based animation, button

基本技術要求:
- 模型建構: 指針與背板(如圖所示)，選擇合適的配色。XY plane,初始在+Y方向
- 運動:依real-time順時針旋轉, 使用於60秒內之計時
- 碼表功能:可以由按鈕暫停(PAUSE, RESTART)

進階技術要求:
- 不同display style: 扇形，或其他
- 運動:連續，或quartz style

[Click here to see my Homework 1](https://jean11231.github.io/CG/hw1/hw1.html)

## Homework 2  (Due 11/12/17) :git & github , README.md

根據上課所說的，將本學期作業的資料夾建成repository
- 建立index.html，為本學期的作業做一個title page
- 上傳到github的gh-pages上
	- index.html中：
	將有每次作業的animated gif以及url link.
	把hw1改成html 並將資料填入
	有link to your email account (以便通知作業有瑕疵需要補正）
	格式參考 : [範例](http://jyunming-chen.github.io/tutsplus/)

- 參考[markdown files](https://help.github.com/articles/basic-writing-and-formatting-syntax/)的格式，為homework repository加上合適的readme.md (參考[學長的範例](https://github.com/ikatyang/javascript-development-guide/blob/master/README.md)）

## Homework 3  (Due 11/27/17) : Hierarchical Model
1. 建構坦克模型：

- 正確的機構(kinematic)[模型](http://web.cse.ttu.edu.tw/jmchen/cg/fall17/tank.html)，以及合理的joint angle limits
- 架設合適的燈光，設定合適的顏色
2. 砲彈發射：

- 初始位置：砲口; 發射方向：砲管方向; 發射速率：固定
- 砲彈打到地面(y=0)即停止。停止後，才可以發射下一發砲彈。
- [雜研與專題生] write "class" for cannonball, 使得可以發射多發砲彈, [reference](https://docs.google.com/presentation/d/17tTiIvHCruuUXcSnboq1dPTnf0tQtg53xqUdj3nE2zw/edit#slide=id.p)
3. 簡單遊戲：

- 坦克在中線(x = 0)上前後運動
- 地圖的兩端(x = 100, x = -100)隨機產生標靶
- 操作坦克，將標靶擊落
- [bonus] 分隔畫面: god's eye view 以及 坦克操作員視角（以便瞄準）

[Click here to see my Homework 3](https://jean11231.github.io/CG/hw2/hw2.html)

## Homework 4  (Due 12/10/17) : OBJ model, Kinematic Drive, Rectangle-Circle Intersection, Dual Viewports

- 在網路上找合適的車輛模型 (OBJ/MTL format)
- 利用合適的loader將其匯入three.js 場景中，以適當大小呈現
- 運用課堂上所教的“kinematic drive"，以鍵盤控制車輛
- 在場景中佈置大小不同的圓形障礙物。可以用threejs所提供的geometry, 或是使用circular billboard (with cut-out texture)
- 實作collision detection程式，使得車輛與障礙物相撞時立即停止。使用者須自行將車輛駛出。請務必在所錄的animated.gif中示範此效果
- 螢幕分割成左右兩viewports: 一邊為上帝視角 (god's eye view), 一編為駕駛的第三人稱視角 (third person view)

[Click here to see my Homework 4](https://jean11231.github.io/CG/hw3/hw3.html)

## Homework 5  (Due 12/22/17) : Class, Raycaster, Shadow Map

- 在網路上找合適的檯燈及椅子模型 (OBJ/MTL)
- 利用合適的loader將其匯入three.js 場景中，以適當大小呈現
- 利用BoxGeometry以及合適的材質做出書桌
- 書桌上放置檯燈以及燈光遙控器 
- 遙控器上有至少兩個按鈕，以控制檯燈以及室內燈光。
- 場景內的燈光與物件皆須作shadow map
- 開關須以class實作，由滑鼠點按觸動
- [Bonus] 以 PD Control實作燈光之light up/dim out effect

[Click here to see my Homework 5](https://jean11231.github.io/CG/hw5/hw5.html)