课件/MP3/电影 都打不开
############################

一直用得很好，但突然之间，课件/MP3/电影 都打不开了，软件提示错误：


  **不能播放该文件！原因：Access violation at address xxxxxxxx in module 'aboboo.exe'...**

  .. image:: /images/troubleshooting/user-data-damaged.png

这可能是您的用户数据文件损坏了，试试这个办法：

1. 如果Aboboo正在运行，请退出Aboboo。

2. 找到用户数据目录，重命名或者移动到别处。（用户数据目录默认在“我的文档\\Aboboo\\udt”，如果您使用便携版本或改动过设置，请参考 :ref:`《数据目录设置》 <preference-data-directory>` ）

3. 再次运行时，Aboboo会重建用户数据（一分钟内完成），重建后能正常打开课件/mp3/电影。

4. 已损坏的用户数据可能无法修复。
