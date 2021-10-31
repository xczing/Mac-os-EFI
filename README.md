# Mac-os-EFI

## 神舟战神Z7M-KP7S1的黑苹果EFI文件

| 设备       | 型号                      |
| ---------- | ------------------------- |
| 笔记本型号 | 神舟z7m-kp7s1             |
| 主板       | 蓝天 N85HJ                |
| CPU        | i7-7700HQ                 |
| 集显       | HD630                     |
| 独显       | Nvidia GTX 1050ti(已屏蔽) |
| 声卡       | ALC269VC                  |
| 无线网卡   | Inter Wireless-AC 3168NGW |
| 有线网卡   | RTL8411B                  |

该EF文件主体来自于[Xin9912](https://github.com/Xin9912/Hackintosh)大佬，基于他的模版适配该机型

在big sur 11.2.3上完美度90%，若有类似机型，酌情参考

### 目前已知问题

1. “可能”CPU无法变频
2. ps2模块无法升级，否则触摸板失效
3. 无线网卡需搭配[HeliPort](https://github.com/OpenIntelWireless/HeliPort)使用，若想使用Wi-Fi管理，需在配置文件中取消[itlwm](https://github.com/zxystd/itlwm)模块
4. 偶发声卡失效，重启即可



基于open core 6.8

三码已去除，请按需求填入

**电脑已坏，该仓库停止更新**
