板载RGB
======

RGB LED控制类指令，用于控制掌控板的3颗RGB ws2812灯珠，rgb对象为neopixel的衍生类，继承neopixel的方法

rgb[n] = (r, g, b)
-------------

**描述：**  设置对应灯珠的颜色，n 为板载RGB灯的个数，第一个灯为0， r、g、b 为颜色亮度值，范围值为0~255


rgb.write()
-------------

**描述：**  把数据写入RGB灯珠中


rgb.fill( (r, g, b) )
-------------

**描述：**  填充所有灯珠颜色及亮度， r、g、b 为颜色亮度值，范围值为0~255


示例
^^^^^

.. image::  /images/blocks/RGB/example/RGB.png
    :scale: 80 %

:download:`点击下载图形化示例</../examples/RGB/RGB.xml>`
