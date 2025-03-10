星际争霸2游戏翻译器
=================

星际争霸2诸位mod作者，大家好。我是来自喵喵呱呱团队的孔明。星际争霸2游戏翻译器是我们为星际2社区开发的众多开源项目之一。该工具能够帮助作者将自己的MOD翻译为多种语言。我们希望该工具能够帮助全世界的星际2MOD作者以及游戏玩家。通过翻译的方式促进作品的推广和交流。

在开发过程中我们结合自己的经验，制作了许多实用功能。该工具支持备份，修改，文本比较，并且支持同语种校对、文本筛选、游戏内效果预览等功能。你甚至不需要使用完整的MOD或地图文件就可以进行翻译工作。因此该工具也适合玩家或项目合作者独立工作使用。
GG&GL!

使用说明
=======


工具栏
============

![image](Image/Tool02.png)

1.文件
------------

新建
--------

>新建一个翻译项目，软件会要求你选择以组件文件夹形式保存的地图文件，双击ComponentList.SC2Components打开即可。使用组件文件夹可以加快地图的读取速度，当应用翻译结果时，对应的翻译文本会自动保存到enUS.SC2Data等本地化文件夹中。

打开
--------

>打开一个保存的项目文件，当你的项目曾经保存过，会生成一个SC2Gametran文件，该文件保存有翻译所需的全部信息。因此你可以在无需地图完整文件的情况下继续翻译工作。

保存
--------

>将你的翻译修改保存为SC2Gametran文件。

另存为
--------

>将你的翻译修改保存为一个新的SC2Gametran文件。

关闭
--------

>关闭软件。

应用翻译
--------

>将你的翻译内容覆盖到组件文件夹中，这会同时修改游戏中的文本。

重载翻译
--------

>从另外一个项目文件中将翻译内容导入至该项目。修改你的翻译内容，你可以选择导入全部或部分语言。

重载文本
--------

>从另外一个项目文件中将翻译内容导入至该项目，但不会修改翻译内容，而是进行文本对比，方便你查看哪些文本的翻译发生了变化。（默认隐藏，需要在主翻译区勾选相关选项）

预览文本
--------

>生成预览翻译结果的Galaxy脚本。可以勾选如下图①对应的复选框来选择预览的文本（可以点击②对应的复选框来全选或全不选当前筛选出的文本，注意，不会更改因筛选不匹配而隐藏的行的状态，但是隐藏的文本也不会加入到预览文本中），最终点击③对应按钮生成预览Galaxy脚本并加入到剪切板中。然后将生成的Galaxy代码加入地图测试用触发器的自定义脚本动作中。启用地图即可预览结果。

![image](Image/Preview.png)
![image](Image/PreviewEditor.png)
![image](Image/PreviewGame.png)

2.筛选记录
--------------

上一纪录/下一记录
------------

>当使用筛选或搜索工具后，主翻译区的文本显示会发生变化，使用该工具可以切换显示状态。

3.翻译语言
-----------

>选择你本次翻译的原始语言和目标语言，如enUS翻译至zhCN。当你的原始语言和目标语言相同时，你可以对翻译文本进行修改和校对。


4.搜索
-------------

>使用搜索工具能够筛选显示你需要的特定内容。搜索设置包含搜索范围，大小写匹配和表达式搜索等实用工具。

5.过滤器
-------------

所属Galaxy文件
--------------

>筛选显示来自不同Galaxy文件的文本。如LibLIB1, LibIB1h等。

所属文本文件
---------------

>筛选显示来自游戏、数据、触发器的文本。

文本状态
--------------

>筛选显示已修改和未修改的文本。这些信息也会在翻译区用颜色进行标记和区分。

使用状态
--------------

>筛选显示游戏中文本的实际使用状态，如新增文本，修改文本，删除文本等，需要与`重载文本`功能配合使用。




翻译复制工具
-------------

翻译复制工具用于将已经翻译好的语言文本覆盖到其他语言文本中。比如在法语或德语文本中使用英文文本。
![image](Image/Tool08.png)

1.目标语言
-----------

>在下拉框中选择一种或多种目标语言，这些语言的文本将被覆盖。

2.来源语言
-----------

>选择一种来源语言作为翻译覆盖的来源。

3.开始复制
-------------

>点击该按钮将文本覆盖到选定的区域语言文本中。


翻译区
==================

![image](Image/Tool04.png)

1.数据编号
-----------

>文本的唯一序号。

2.文本ID
--------------

>文本在编辑器中的ID。

3.所在文件
--------------

>标记文本的来源。

4.文本状态
------------

>显示文本的修改状态。

5.使用状态
------------

>显示文本在游戏中的使用状态，右击翻译区表格栏可以勾选是否显示。

6.舍弃文本
--------------

>默认和原始文本保持一致。可以使用`重载文本`进行加载，此时将显示`旧版本mod`的文本信息，用于和当前文档进行比较。

细节视图
==================

![image](Image/Tool06.png)

1.显示语言
-------------

>显示游戏中激活的区域语言。比如示意图中显示本mod包含英语、韩语和中文三种语言。

2.游戏文本数据
------------------

>显示在所有区域语言下文本的内容，注意此处仅支持文本的查看，不支持修改功能。

3.修改文本
---------------

>与翻译区的修改文本文本框功能相同，提供更大的空间，方便较长文本的翻译和阅读。




4.Galaxy拼接结果
--------------------

![image](Image/Tool10.png)
>显示文本在Galaxy脚本中的详细信息，当一个句子由多个字符串组成时，也可以通过该工具查看完整的拼接文本。如“`造成`+`点伤害`”。
