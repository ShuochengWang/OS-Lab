## 简易微内核操作系统

- 基于C和汇编
- 保护模式
- 五态进程
- 多进程
- 信号量
- 多终端
- 命令控制
- 键盘输入
- 快捷键
- 无缓冲的进程间通讯
- 微内核
- 类unix（inode）文件系统。

---

## Simple micro-kernel operating system

Developed a simple micro-kernel operating system in a bare computer (virtual machine). The system was developed using C and assembly language in protected mode. 

The system supports following features: 
- five state process
- semaphore
- multi-process
- multi-terminal
- fork
- command control
- keyboard input
- shortcut keys
- Unix-like file system (inode)
- unbuffered IPC
- micro-kernel

---

myos为源代码

不同运行环境选择不同压缩包：
- linux下运行环境 ： 
  - ubuntu14.04，使用bochs测试正常。
- windows下运行环境： 
  - 64位win7，使用bochs2.6.8测试正常。

致谢：凌老师，以及《ORANGE’S：一个操作系统的实现》