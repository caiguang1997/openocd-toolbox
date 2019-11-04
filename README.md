# openocd-toolbox
openocd是一个开源的调试软件，称之为世界上最强大的开源调试软件并不为过，经过数十年的开源社区的推动发展，当今其可调试数百种目标芯片，包括arm, mips, dsp, fpga, cpld等。支持多种调试接口，如cmsis-dap, jlink, stlink, usb-blaster等。  
以下是一些基于cmsis-dap接口的调试脚本，可以对目标芯片完成擦除、烧录、锁定等操作，当然您也可以自行修改脚本，以完成自己的定制需求。  
使用非常简单，**无需安装任何额外软件，以及额外的配置，您只需将本仓库下载下来，双击其中脚本即可运行，实际使用会比图形界面操作更加高效，也更加强大** 。  
当前支持如下平台的操作  
- stm32f1x  
- stm32f0x

若您有需求，请在本仓库的issue中上报新平台，脚本会持续更新。
