开箱清单
=========

荔枝派主板及相关配件如下，请对照自己的购买清单清点：

- 荔枝派主板
   + 分为板载wifi版和板载USB版，二者互斥，所以选择wifi版的板子上是没有焊USB母座的，请知悉。
   + 主板上默认没有焊接双排插针，请自己动手焊接

      - *此处应有对比图片，请好心人补充。。*

- 板载wifi
   + 默认板载wifi模块是RTL8723BU模块，支持WIFI+BT4.0双模
   + 天线接口是IPEX座子，配有一根PCB软天线或者铜棒天线
   + 天线座前面的pi型匹配电路有一个电容是NC的，不是掉了，请知悉。
   + *此处应有图片，请好心人补充。。*

- 摄像头模组
   + 摄像头模组有OV7670（30W）和OV2640（200W）两种，外型上来说，OV7670摄像头更薄，OV2640摄像头更厚
   + .. image:: ../_static/概览/2.list.png
        :width: 400px
   + .. image:: ../_static/概览/3.list.png
        :width: 400px
   + 两种摄像头的供电电源不同（2640的一路电源是1.3V，而7670的一路是1.8V），虽然实测并不会对摄像头造成永久性损伤，但还是建议在没有配置好正确的电源前不要插上摄像头
   + **摄像头模组很小，请收货时注意不要乱丢包装，可能会被卡在包装盒中**
   + .. image:: ../_static/概览/4.list.png
        :width: 400px
   + 摄像头插入方向 ： FPC座为下接，摄像头朝正面插入

- LCD屏
   + 目前配件中的屏幕是5寸和6寸的40P RGB屏，分辨率800*480
   + 由于近期屏幕价格飞涨，配备的是拆机屏，屏幕边框及排线上可能附着屏蔽用铝箔纸，请知悉。<发货的是品相较好无锈痕的，群主还剩下一堆战斗橙色的屏幕，价格好商量>
   + 屏幕插入方向：FPC座同样是下接的，屏幕朝正面插入

- VGA转接板
   + vga转接板与荔枝派主板使用FPC软排线连接，FPC座子都是下接的。
   + 连接完成后，使用VGA线接到显示器即可显示，注意屏幕分辨率等参数需要在fex中设置

- 亚克力外壳
   + 亚克力外壳使用4组螺柱螺母固定板子
      - > 此处应有图片

- OTG转接头
   + 用于将OTG口转为 USB-A母口

- USB HUB+网口模块
   + 可以拓展3个USB口和一个以太网口，免驱

**需要另配的配件**

- tf卡
   + 系统是存储在tf中的，不插卡是不能启动系统的
- 耳机
   + 荔枝派使用的耳机是美式耳机标准，不同标准的耳机可能mic不会工作，详见荔枝派 原理图_。
   
.. _原理图: https://github.com/Zepan/ilichee/blob/master/%E8%B5%84%E6%BA%90%E6%96%87%E4%BB%B6/Lichee%E5%8E%9F%E7%90%86%E5%9B%BE.pdf