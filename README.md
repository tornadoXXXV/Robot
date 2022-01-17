# Sorting Robot
![gif](https://github.com/tornadoXXXV/Robot/blob/main/images/motor.gif)
<img src="https://github.com/tornadoXXXV/Robot/blob/main/images/complete.png"> 
<img src="https://github.com/tornadoXXXV/Robot/blob/main/images/box2.png" width=60% height=60%>
  
大学内講義にて5人1組で自動走行・自動分別ロボットを作成。自動分別機能を私が担当した。  
raspberryPiにカメラを取り付け、映ったものがペンか消しゴムかを判断する。しきい値を0.75とし、75%以上の確率でどちらかであると判断できた場合に片方のモータが動作し、それに連動して扉が開く。  
raspberryPi上でall.pyを実行することで使用できる。

# Wiring
<img src="https://github.com/tornadoXXXV/Robot/blob/main/images/wiring.jpg"> 

# References
川島賢『画像認識プログラミングレシピ』株式会社 秀和システム https://github.com/Kokensha/book-ml  
DEVICE PLUS 「ラズパイ電子工作の基本① サーボモータを使って指さし温度計を作っ
てみよう」 https://deviceplus.jp/hobby/raspberrypi_f01/  
Raspberry Pi とサーボモータで踊るはにわ制作 https://dotstud.io/blog/dancing-haniwaservo-raspi/
