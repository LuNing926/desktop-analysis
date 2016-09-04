#1、java文件结构及说明
![image](https://github.com/openthos/desktop-analysis/blob/master/image/java_structure.png)

|文件名|说明|
|------|----|
|BasicActivity.java|模拟壁纸，Launcher3中实际为Launcher.java|
|MainActivity.java|主界面，继承壁纸|
|MainActivity1.java|主界面，继承壁纸，第二版，目前已废弃|
|HolderCallBack.java|拖动接口|
|HomeAdapter.java|主界面icon适配器|
|HomeGestureDetector.java|已废弃|
|ItemCallBack.java|拖动回调工具类|
|MenuAdapter.java|目录适配器，已废弃|
|RecycleCallBack.java|拖动接口|
|Type.java|枚举，声明桌面每个区域的类型，有computer,recycle,file,directory,blank五大类，可扩展|
|DiskUtils.java|磁盘数据工具类|
|FileUtils.java|文件处理工具类|
|OtoConsts.java|常量|
|MenuDialog.java|右键菜单对话框|
|PropertyDialog.java|属性对话框|
|WindowsLayout.java|自定义桌面ViewGroup,MainActivity1.java使用|

#2、布局文件结构
![image](https://github.com/openthos/desktop-analysis/blob/master/image/xml_structure.png)

|文件名|说明|
|------|----|
|activity_background.xml|模拟壁纸所用的布局|
|activity_main.xml|MainActivity所用的布局|
|activity_main1.xml|MainActivity1所用的布局|
|dialog_menu.xml|右键菜单对话框的布局|
|dialog_property.xml|属性对话框的布局|
|item_icon.xml|桌面每个icon的布局|
|item_menu.xml|右键菜单每个item的布局|
