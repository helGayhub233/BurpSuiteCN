<h1 align="center">BurpSuiteCN 汉化启动器</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-21+-orange.svg" alt="技术栈"/>
  <img src="https://img.shields.io/badge/Burp-2026.x-purple.svg" alt="支持版本"/>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=helGayhub233.BurpSuiteCN" alt="访问次数"/>
  <a href="https://github.com/helGayhub233/BurpSuiteCN/releases"><img src="https://img.shields.io/github/downloads/helGayhub233/BurpSuiteCN/total" alt="下载次数"/></a>
</p>

<table>
  <tr>
    <td><img src="https://github.com/helGayhub233/BurpSuiteCN/blob/main/images/demo-1.png" width="100%"/></td>
    <td><img src="https://github.com/helGayhub233/BurpSuiteCN/blob/main/images/demo-2.png" width="100%"/></td>
  </tr>
  <tr>
    <td align="center">适配新UI（v2026.6）</td>
    <td align="center">从繁到简，从能用到好用</td>
  </tr>
</table>

## 📦 快速开始

1. 将Jar文件放置在程序目录 `mv burpsuiteloader.jar`
2. 在 Burp Suite 安装目录中找到并编辑 `vmoptions.txt`
3. 编辑现有条目或新增条目：

```
# DO NOT ADD OR CHANGE JVM OPTIONS IN THIS FILE
# This file may be overwritten when Burp Suite is launched or updated.
# 
# To configure Burp Suite's Java Virtual Machine (JVM), use the user.vmoptions file instead.
#
# Specify options in the user.vmoptions file, by adding each one on a new line.
# For example, the following option limits Burp Suite to using 50% of the system's total RAM:
# -XX:MaxRAMPercentage=50
#
# For more information about configuring options for Burp's JVM, see:
# https://portswigger.net/burp/documentation/desktop/troubleshooting/setting-java-options

-XX:MaxRAMPercentage=50
-include-options settings.vmoptions
-include-options user.vmoptions

--add-opens=java.base/java.lang=ALL-UNNAMED
--add-opens=java.base/java.lang.reflect=ALL-UNNAMED
--add-opens=java.base/java.io=ALL-UNNAMED
--add-opens=java.base/java.util=ALL-UNNAMED
--add-opens=java.base/java.security=ALL-UNNAMED
--enable-native-access=ALL-UNNAMED

-javaagent:burpsuiteloader.jar=loader,chs
```

4. 配置完成后，直接使用以下方式启动：
   - 双击 Burp Suite 应用
   - 启动脚本 / 快捷方式

## ⚠️ 免责声明

本项目仅供学习交流使用，请支持正版软件。
<br>
## 📄 License

<a href="https://github.com/helGayhub233/BurpSuiteCN/blob/main/LICENSE">MIT License</a>
