# jean-0313.github.io
#影片網址:https://drive.google.com/file/d/1vqInTx0UDanpiU29ZbJFNIrUQ090zqTF/view?usp=sharing

#主題簡介:彈跳大挑戰，這是一款以滑鼠控制板子使球反彈的遊戲，遊戲目標是不要讓球落地，若球落地則會損失一條命，玩家需要在有限的生命數中擊碎所有長條物，擊碎所有長條物則過關，總共分為三關。

#使用者如何使用?
1.一開始是進到遊戲介紹的頁面，使用者閱讀完遊戲規則後按"開始遊戲"，即可進入第一關
2.使用者需要以滑鼠控制板子左右移動，使球反彈擊碎所有長條物
3.在使用者過關之後會出現一個過關的彈跳視窗，點下確定即可前往下一關
4.當使用者的生命數量減為0時，會出現game over的彈跳視窗，按下確定即可重來
5.使用者可以選按上一關、下一關的按鈕在三個關卡中自由切換
6.當第三關也過關時會出現挑戰成功的彈跳視窗，按下確定會返回第一關

#製作流程:
在這次的專題當中，我融合了html,css以及javascript的使用，並在javascript當中使用canvas這個js函式庫來協助我完成這個小遊戲，在js當中我大量地使用funciotn函式使網頁html元件移動的效果會符合遊戲規則、並使用addEventListener，來監測使用者的滑鼠移動，並且使其和html元件的移動結合;另外，在css當中我也使用了hover的技巧，增加網頁和使用者的互動。而在整個遊戲的排版及配色都是我自己決定的，希望使用大地色能夠帶給使用者比較溫柔的感覺。此外，我還應用了button以及location.href的程式碼來設計跳轉頁面的互動效果。

#亮點:
這次的專題中，我的遊戲原型是根據參考資料的教學而製成，不過參考資料的教學只有教最基本(也就是我的遊戲的第一關)，剩下的第二關及第三關是我自行改編程式碼，增加長條物的數量以及球移動的速度，為遊戲增加創新。此外，因為我自行增加了多個關卡，因此我也自行研究，將程式碼改編成可以跳換頁面來達到更換關卡的效果。

#參考資料:https://developer.mozilla.org/zh-TW/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript