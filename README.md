# HMI_UI

### 本分支主要是洗涤车界面，串口屏代码

### 5寸屏，电阻屏，分辨率800*480

回头补上动图

### 交互命令：

| 序号 | 命令               | 示例                                                         | 发送方 |
| ---- | ------------------ | ------------------------------------------------------------ | ------ |
| 1    | 启动完成           | mt_mode.va_started.val=1                                     | 主机   |
| 2    | 开启刷盘           | open brush                                                   | 屏幕   |
| 3    | 关闭刷盘           | close brush                                                  | 屏幕   |
| 4    | 开启吸水           | open water                                                   | 屏幕   |
| 5    | 关闭吸水           | close water                                                  | 屏幕   |
| 6    | 前进               | open  direction                                              | 屏幕   |
| 7    | 后退               | close  direction                                             | 屏幕   |
| 8    | 更新电量           | mt_mode.va_battery.val=66                                    | 主机   |
| 9    | 激活充电标志       | mt_mode.va_charging.val=1                                    | 主机   |
| 10   | 设置水量           | mt_mode.va_water.val=66                                      | 主机   |
| 11   | 里程计整数         | mt_mode.va_odom_int.val=10                                   | 主机   |
| 12   | 里程计小数         | mt_mode.va_odom_f.val=234                                    | 主机   |
| 13   | 设置地图列表       | mt_mode.va_map_list.txt="default;map1;map2"                  | 主机   |
| 14   | 设置地图数量       | mt_mode.va_map_num.val=3                                     | 主机   |
| 15   | 设置启动的地图名称 | map:map1234                                                  | 主机   |
| 16   | 暂停               | pause  status                                                | 屏幕   |
| 17   | 继续               | working  status                                              | 屏幕   |
| 18   | 进度               | mt_mode.va_p.val=10                                          | 主机   |
| 19   | 速度               | mt_mode.va_s.val=110 单位cm/s                                | 主机   |
| 20   | 效率               | mt_mode.va_x.val=3600 m²/s                                   | 主机   |
| 21   | 坐标               | mt_mode.va_x_point.val=12  mt_mode.va_y_point.val=34  mt_mode.va_z_point.val=56 | 主机   |
| 22   | 停止工作           | stop  working                                                | 屏幕   |

 

 

 