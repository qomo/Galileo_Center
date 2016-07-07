# Galileo_Center

要把给我幸运的第一代Galileo开发版做成家里的智能中心，它现在已经连上了一个廉价的intel wifi 5100，和一个1T的移动硬盘。  
wifi配置用了connmanclt工具，具体配置过程参见https://software.intel.com/en-us/blogs/2014/04/25/wireless-galileo-on-yocto-linux-iot-devkit-image  
硬盘还没有跑起来。  
我要先做这样一个功能，Galileo上电后自动以10s每次的频率向局域网广播它的IP地址，这样我才可能在没有屏幕和串口的情况下知道要如何与它联系  
在未来，我还希望将我闲置的小TTL屏幕接上，用于显示基本的信息，如IP地址。甚至加上几个简单的按键，实现新wifi环境的手动配置。
