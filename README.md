 同 步 源 码
---------------

要使用NexusCN ROM, 首先你要获取[Repo](http://source.android.com/download/using-repo).

初始化你的本地仓库:

    repo init -u git://github.com/NexusCnMod/android.git -b android-4.4

然后同步命令:

    repo sync

执行编译:

     cd <源码目录>
     . build/envsetup.sh
     brunch <你的设备名称>
