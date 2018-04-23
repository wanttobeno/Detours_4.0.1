




Detours早就知道大名了，网上都说Detours x64需要商业授权。

所以都是在网上找了各种的Hook引擎。

没想到Detours4.0.1早在几年前就开源了，还是MTI开源协议的。

----

4.0.1 跟 Deours 3.0 Bulid 343 是一样的代码，只是更新了协议。

官网说明：[Microsoft](https://www.microsoft.com/en-us/research/project/detours) [Github](https://github.com/microsoft/detours)

---
Detours 4.0.1 supports x86, x64 and other Windows-compatible processors (IA64 and ARM). It includes support for either 32-bit or 64-bit processes.

---
###编译说明：

```c
nmake Makefile'
```

---

另外包含了许多的使用例子。

例子说明：

Hook例子： comment

cping：Ping Network Server

disas：反汇编

dtest：Hook函数带参数测试。从带1个参数的函数到16个参数的函数测试

dumpe：显示dll文件的接口

dumpi.exe: 显示exe，dll文件的所有依赖dll，并打印调用dll的接口。

echonul：无

einst: 显示自身加载的所有dll和基址。

excep：异常捕获

findfunc：显示自身加载的所有dll和基址。

impmunge：显示dll和dll接口符号。

managed-x86：显示dll，dll基址，路径。

member:类个共有接口的替换。

region：测试不同的系统区域边界

size：命令行启动，传参。

sleep5：Sleep(5000)

sleepbad: Sleep系列定时器hook

sleepnew：Sleep系列定时器

sleepold：Sleep系列定时器

sltest： 无

sltestp和sltest：测试管道、关键段，创建文件等hook，

symtest：使用windbg.dll加载符号，显示符号信息。

testapi：Attach，显示虚拟内存中所有的dll和地址，地址大小，内存属性。

tracebld：dll注入，记录读取，创建，删除，移动文件等操作，支持导出为xml。

tryman32：显示调用的dll是x86还是x64。

withdll：参数 /d:test.dll /v  xxx.exe。dll注入exe程序，打印内存区段信息。
























