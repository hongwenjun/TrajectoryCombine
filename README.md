# TrajectoryCombine
百度导航4.7.0版本 轨迹分析工具  百度轨迹GPS: 轨迹记录文件导出Gps点

***
E:\BaiduNavi\06版bdgps.exe
百度轨迹GPS: 轨迹记录文件导出Gps点(1/60，支持gz格式) BY Hong Wenjun 2015.1.9

示例1: D:\>bdgps.exe  test.bin [或者 test.bin.gz]

示例2: D:\>bdgps.exe  test.bin.gz  gps.txt

示例3: D:\>bdgps.exe  test.bin.gz  gps.txt  -ALL

示例4: D:\>bdgps.exe  test.bin.gz  gps.txt  -100


输出文件不填，结果显示在屏幕上  <用-ALL或者数字参数，设置分数>
***
E:\BaiduNavi\06版TrajectoryCombine.exe
Usage: TrajectoryCombine.exe  test.bin.gz  [test2.bin.gz ...]
***
支持百度导航4.7.0和之前版本
TrajectoryCombine\BaiduNavi_APK\百度导航4.7.0版.apk

***
现在百度导航已经合并到百度地图
百度地图 的轨迹文件 在 /mnt/sdcard/BaiduMap/bnav/TRAJECTORY 目录下
![image](https://github.com/hongwenjun/TrajectoryCombine/raw/master/img/traj_dir.png)
***


使用工具按 -300 参数 就是 5分钟 取几个gps坐标，
然后转到 google 地图 生成导航路线

![image](https://github.com/hongwenjun/TrajectoryCombine/raw/master/img/gps_on_maps.png)




