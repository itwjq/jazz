一.jazz的烧写方法
  1.内核烧写
	1.将要烧写的内核文件放到烧写器中jazz_RS800_web_148\Profiles\MX23 Linux Update\OS Firmware\files目录下，
	2.修改jazz_RS800_web_148\Profiles\MX23 Linux Update\OS Firmware该目录下的ucl.xml文件，将ucl.xml文件中的第27行以及第54行中的updater.sb文件替换成要烧写的文件名。
	3.点击烧写器中MfgTool.exe,点击Options->configuration-?profiles,“选项”一列选择singlechip NAND
	4.点击“扫描设备”发现驱动后点击“开始”，等待完成即可

  2.测试
	1.连接板子的两个USB插口，找到计算机中的设备管理器，点击端口，查看安装驱动的端口是多少
	2.打开putty，点击“串口”，填写端口号，speed填写为115200 点击开始即可