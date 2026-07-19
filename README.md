# xueersi_xiaomiao_gd32_firmware
学而思小喵掌机GD32固件

基于https://github.com/ZyoungInc/xueersi-idf 添加代码修改而来  
感谢大佬的辛勤工作  

功能描述  
正面底部Rst键添加背光调节功能，一共5档，调整后延时3秒保存到GD32内部Flash。

使用方法  
下载文件并解压，找到\GD32_firmware\Project\MDK-ARM\app_out.bin  
使用jlink，daplink等等工具烧录到0x08000000地址  
