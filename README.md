关于mathtype修改试用期和手写输入提供详细步骤
1、在网上下载mathtype中文版
2、新建记事本并输入
Windows Registry Editor Version 5.00
[-HKEY_CURRENT_USER\Software\JavaSoft\Prefs\com\wiris\editor\license\]
[HKEY_CURRENT_USER\Software\JavaSoft\Prefs\com\wiris\editor\license\]
"/Cv/E/C81+j/Rw/U/E6ws/Znt/Os/K/Q=="="11/M/P/Ir/Y/B/S/P/Pr/Q/L/Ny/T9s4/Iw=="
"/Mz/Bhef/D/Q/Hs30/U6/F/Pdl/R/Xsg=="="/S/Zd8c/Ai/Z/A83028s6/Kn/Gf/M/Q=="
"vi/L/M7/K/Hb/C/O/A/K/X9uuis/O1/J/A=="="/S/Zd8c/Ai/Z/A80\\/O/S/C/Vgp\\0/P/Q=="
"wm/U/C/Y/T/Nz5/Tw="="/Wna/F/W3q/I/Yp/V\\lj/Dedai56/Ur/Wpf/P/Kpl/Soh/A/Z/Qe\\6hit3ym\\6m5sp/B/B/Q=="
"x/W/Yrj/M/Db/Bds="="104z/W8rbqpw5\\/Qz0/C/Q/Opu/Dj/B5b/Dwsy77"
将后缀名修改为reg，然后运行，此时mathtype试用期被修改
3、找到路径C:\Program Files\Common Files\microsoft shared\ink将mip.exe文件粘贴到该路径
4、如若使用的是win11系统此时手写功能并不能使用还需将mip.exe.mui文件粘贴到路径C:\Program Files\Common Files\microsoft shared\ink\en-US\
5、mip.exe.mui文件原本存在于win10系统中，这里不需要利用虚拟机下载直接给出文件
