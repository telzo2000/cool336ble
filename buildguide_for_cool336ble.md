# Build guide

back side of PCB（PCBの裏面）


![](img/img00002.jpg)


## Build 1

### 1 Diode soldering

![](img/img00004.jpg)

Solder the diodes to the back of PCB.
<br>
PCBの裏面にダイオードのハンダ付けをします。
<br>
There are lead type and SMD diodes.
<br>
ダイオードはリードタイプか、SMDがあります。
<br>
Here, we will explain the lead type soldering.
<br>
ここでは、リードタイプのハンダ付けの説明をします。
<br>

Use a lead bender to bend the legs of the diode.
<br>
リードベンダーを使い、ダイオードの足を曲げます。
<br>
Insert the diode into the board.
<br>
ダイオードを基板に挿しこみます。
<br>

Please pay attention to the orientation of the diode.
<br>
ダイオードの向きに注意してください。
<br>

![](img/img00003.jpg)

Please solder.
<br>
はんだ付けをしてください。
<br>
<br>
Then, cut off the excess lead with nippers.
<br>
その後、余ったリードをニッパーで切り取ってください。


[８倍速　Diodeハンダ付け動画](https://youtu.be/Yaodh2-XxV4)

<br>
<br>


### 2 Switch socket soldering

![](img/img00006.jpg)

Solder the switch sockets on the back side.
<br>
裏面にスイッチソケットのハンダ付けをします。
<br>

![](img/img00005.jpg)


[８倍速　Switch socketハンダ付け動画](https://youtu.be/E__mHvmIXQo)



### 3 Reset switch soldering

Insert the reset switch from the back of the PCB and solder the exposed part.
<br>
リセットスイッチをPCBの裏面から差し込んで、表面に出た部分をはんだ付けしてください。
<br>

![](img/img00007.jpg)

![](img/img00008.jpg)

![](img/img00009.jpg)


[リセットスイッチのはんだ付けの作業動画](https://youtu.be/Pl24Exfh8b8)



### 4 Battery parts soldering(Bluetooth option)

![](img/img00018.jpg)

Solder the slide switch first.
<br>
最初にスライドスッチをはんだ付けします。
<br>
![](img/img00014.jpg)

Insert the switch from the back of the PCB with the switch knob facing outward.
<br>
スイッチのつまみが外側に向くようにして、PCBの裏面から差し込みます。
![](img/img00015.jpg)

After temporarily fixing it with masking tape, etc., solder the exposed part of the PCB.
<br>
マスキングテープなどで仮固定をしてから、PCBの表面に出た部分をはんだ付けします。
![](img/img00016.jpg)
<br>


[スライドスイッチのはんだ付けの作業動画](https://youtu.be/5nkRklibay4)

<br>
Next, solder the capacitor.
<br>
次に、コンデンサをはんだ付けします。
<br>
<br>
First, apply solder to only one side of the two pads.
<br>
最初に、２つあるパッドの片側だけに、はんだを盛り付けます。
![](img/img00012.jpg)

Place the capacitor and fix it by melting the solder.
<br>
コンデンサを置き、もったはんだを溶かしながら、固定します。
<br>
Solder the capacitor, applying solder to the remaining pads.
<br>
残りのパッドにはんだを盛りながら、コンデンサをはんだ付けします。
![](img/img00013.jpg)
Finally, attach the battery holder.
<br>

[コンデンサのはんだ付け作業の動画](https://youtu.be/8CFiDMtg21s)

<br>
最後に、電池ホルダを取り付けます。
<br>
Insert it from the back side of the PCB and solder the front side. Using masking tape for temporary fixation will make the work easier.
<br>
PCBの裏面から差し込んで、表面をはんだ付けします。仮固定にマスキングテープを使うと作業が簡単になります。
<br>
![](img/img00017.jpg)


### 5a BLE MIcro Pro
Please prepare two con-through (12 pin 2.5mm) instead of the pin header included with BLE Micro Pro.
<br>
ブレマイクロプロ付属のピンヘッダではなく、コンスルー（12ピン 2.5mm）を２つ用意してください。

![](img/img00028.jpg)

There is a small hole in the side of the conthru. Insert it into the PCB, being careful to orient the holes the same way.
<br>
コンスルーの側面に小さい穴が開いています。穴を同じ向きになるよう注意して、PCBに差し込んでください。

![](img/img00027.jpg)

![](img/img00026.jpg)

Insert it into the con-through so that the part with the  BLE Micro Pro parts is visible. If the  BLE Micro Pro easily comes off from the console, we recommend soldering. However, due to the structure of the bottom plate of the 3D printer, I think it will be difficult to remove, so no soldering is necessary.
<br>
 BLE Micro Proの部品が載っている方が見えるように、コンスルーに差し込んでください。もし、 BLE Micro Proがコンスルーから外れやすいときははんだ付けをお勧めします。ただし、3Dプリンタのボトムプレートの構造上、外れにくいと思うので、はんだ付け不要です。
<br>

### 5b Pro Micro
If you are not interested in wireless connectivity, you can keep the price low by using the pro micro.
<br>
もしあなたが無線接続に興味がないのであれば、pro microを使用することで価格を低くすることができます。
<br><br>
Please prepare two con-through (12 pin 2.5mm) instead of the pin header included with pro micro.
<br>
pro micro付属のピンヘッダではなく、コンスルー（12ピン 2.5mm）を２つ用意してください。
<br>

![](img/img00022.jpg)

There is a small hole in the side of the conthru. Insert it into the PCB, being careful to orient the holes the same way.
<br>
コンスルーの側面に小さい穴が開いています。穴を同じ向きになるよう注意して、PCBに差し込んでください。

![](img/img00023.jpg)

Insert it into the con-through so that the part with the pro micro parts is visible. If the pro micro easily comes off from the console, we recommend soldering. However, due to the structure of the bottom plate of the 3D printer, I think it will be difficult to remove, so no soldering is necessary.
<br>
pro microの部品が載っている方が見えるように、コンスルーに差し込んでください。もし、pro microがコンスルーから外れやすいときははんだ付けをお勧めします。ただし、3Dプリンタのボトムプレートの構造上、外れにくいと思うので、はんだ付け不要です。
<br>

![](img/img00024.jpg)

Some of them are soldered.
一応はんだ付けしたものもです。

![](img/img00025.jpg)





### 6a Install firmware （BLE Micro Pro）


Here is an [article](https://sizu.me/m_ki/posts/01s8uea4u7x8) on how to do it.
<br>
ここにやり方の[記事](https://sizu.me/m_ki/posts/01s8uea4u7x8)があります。
<br>


### 6bInstall firmware （pro micro）

There is a hex file [here](https://github.com/telzo2000/cool336ble/tree/main/firmware). Please install it using QMK ToolBox.
<br>

[ここ](https://github.com/telzo2000/cool336ble/tree/main/firmware)にhexファイルがあります。それを、QMK ToolBoxを使って、インストールしてください。


[QMK ToolBox](https://qmk.fm/toolbox)

キーマップ編集サイト
[Vial](https://get.vial.today/)

### 7 Fix the stabilizer

Attach the stabilizer to the surface of the PCB.
<br>
PCBの表面にスタビライザーを装着してください。
<br>
The stabilizer will operate smoothly if it is greased.
<br>
スタビライザーはグリスをしておくと、滑らかに稼働します。
<br>
<br>


### 8 Fix the switch plate(Acrylic) with screws

Insert the FR-4 switch plate, the M2 spacer (3mm), and the M2 screw (8mm) in that order to secure it.
<br>
FR-4のスイッチプレート、M2スペーサー（6mm）の順でM2ネジ（8mm）の順で差し込んで固定します。
<br><br>


### 9 Insert the key switch

Insert the key switch from the switch plate side.
<br>
スイッチプレート側からキースイッチを差し込んでいきます。
<br>
<br>


### 10 Fix the bottom case with screws

Secure the bottom plate with four M2 screws (6mm).
<br>
ボトムプレートをM2ネジ（6mm）４本で固定します。
![](img/img00037.jpg)
![](img/img00036.jpg)


### 11 Complete

Attach your favorite keycaps and you're done.
<br>
お気に入りのキーキャップをつけて完成です。
<br>

I wrote an article about QAZ layout keycaps [here](https://sizu.me/m_ki/posts/4fr24ift68fc).
<br>
QAZレイアウトのキーキャップについて、[ここ](https://sizu.me/m_ki/posts/4fr24ift68fc)に記事を書きました。
<br>

![](img/img00001.jpg)

<br>
Welcome to the world of the best keyboards.
<br>
最高のキーボードの世界にようこそ。
<br>