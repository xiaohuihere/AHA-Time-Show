tspi-drivers/
├── dts/tspi-timewarp.dtsi # 屏、摄像头、旋钮节点在这⾥，⽅便 diff 和回退
├── panel-tspi31/ #  panel 驱动
├── rotary-ec11/ #  旋钮中断驱动
├── vcam/ #  虚拟 V4L2 驱动
├── twmem/ #  dma-buf 帧内存驱动
├── twblk/ #  blk-mq 内存块设备
├── rt-lab/ #  实验脚本（stress-ng、trace-cmd）与数据
└── docs/ # 每个节点的调试记录与数据

硬件：
RK3566 泰⼭派；USB UVC 免驱摄像头；OV5695 摄像头（2-lane，30PIN MIPI）；3.1 ⼨ MIPI 屏 + 转
接板；HDMI 扩展板；EC11 旋转编码器（20 脉冲，带按键开关）；

开发路线：
EC11