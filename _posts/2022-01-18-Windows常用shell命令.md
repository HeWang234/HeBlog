---
title: Windows常用shell命令
categories: [Help]
---

# Windows常用shell命令

CMD

| 命令                                                         | 功能                 |
| ------------------------------------------------------------ | -------------------- |
| `dir`                                                        | ls                   |
| `xcopy D:\A F:\B /T/E`                                       | 复制D:\A中的目录结构 |
| `rundll32.exe user32.dll LockWorkStation`                    | 锁屏（win+L）        |
| `netstat -ano | findstr :10020` <br>`taskkill /F /PID <PID>` | 杀端口               |


VB

| 代码                                                         | 功能 |
| ------------------------------------------------------------ | ---- |
| `Dim WSHShell`<br/>`Set WSHShell=WScript.CreateObject("WScript.Shell")`<br/>`WSHShell.Run "Rundll32.exe user32.dll,LockWorkStation", 0` | 锁屏 |
