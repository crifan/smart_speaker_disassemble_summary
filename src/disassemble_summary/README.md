# 拆解心得

在拆解硬件期间有些心得整理如下：

## `Marking`不是`Part Number`

电路板上芯片标的是`Marking`=`标识`，不是`Part Number`=`芯片型号`

* 如果芯片大的话：往往标识信息也更全，往往可以直接看到`Part Number`
  * 比如
    * [主控芯片 MTK MT8516](http://book.crifan.com/books/smart_speaker_disassemble_summary/website/tmall_genie_candy_cube/chip_info_research/cpu.html)
    * [存储芯片 Samsung K9F1G08U0F](http://book.crifan.com/books/smart_speaker_disassemble_summary/website/tmall_genie_candy_cube/chip_info_research/storage.html)
* 芯片体积很小的话：往往只能看到`Marking`，而不是`Part Number`
  * 比如
    * 标识是`14VF`，对应芯片是：[TI DC-DC转换器 TLV62568](http://book.crifan.com/books/smart_speaker_disassemble_summary/website/tmall_genie_candy_cube/chip_info_research/power_management.html)

* 大多数情况下都可以通过`Marking`找到`Part Number`
* 有时候通过`Marking`也找不到`Part Number`
  * 比如
    * 标识是`T9895`，不是`三星 T9895`，而是[NXP TFA9895](http://book.crifan.com/books/smart_speaker_disassemble_summary/website/tmall_genie_candy_cube/chip_info_research/audio.html)

## 如何拍清楚电路板上的芯片的标识信息

* 最好在`晴天光线好`的情况下拍照
* 最好用`带微距的手机`或`专业相机`
* 还可以借助于`放大镜`拍
