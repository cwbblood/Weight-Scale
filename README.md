# Weight-Scale
使用单片机测量体重，并通过蓝牙传输到Android端进行显示处理

gif图：

<img src="picture/1.gif"  width="360"  height = "780" />

整体图：

<img src="picture/2.jpg" width="720"  height = "540"  style="transform:rotate(270deg);">

需要的硬件部分：

![](picture/3.jpg)



       在单片机端，压力传感器检测到压力后，转为电信号输出，经模数转换模块，将电信号转换
成数字信号传输给单片机，单片机经处理后将体重信息显示在液晶显示模块上。
       通过蓝牙来传输数据，Android端在连接之后能收到单片机端发送来的体重信息，显示体重，
可输入身高计算BMI，并给出相应的体重提示，可将本次体重信息一键分享到微信，可保存每次
测量的体重值、体重平均值，可取消保存，可查看近10次体重曲线图，可显示上次测量的体重，
可显示以往平均体重。