Copy MSCOMM32.OCX to C:\WINDOWS\SysWOW64(If you using 32bit Windows to C:\WINDOWS\SysWOW32) 
Run CMD(as Administrator)
regsvr32 /u C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 /i C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 C:\WINDOWS\SysWOW64\MSCOMM32.OCX
Double click MSCOMM32.reg
enjoy!

第一步，复制MSCOMM32.OCX 到 C:\WINDOWS\SysWOW64(如果是32位系统就是C:\WINDOWS\SysWOW32)
依次运行下面三条命令(以管理员身份运行)：
regsvr32 /u C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 /i C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 C:\WINDOWS\SysWOW64\MSCOMM32.OCX
运行注册控件：
Regedit_MSCOMM32.reg
恭喜可以正常使用MSCOMM32控件了！~
