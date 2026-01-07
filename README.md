<h1 align="center">BurpSuiteCN 汉化启动器</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-21+-orange.svg" alt="技术栈"/>
  <img src="https://img.shields.io/badge/Burp-2025.x-purple.svg" alt="支持版本"/>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=helGayhub233.BurpSuiteCN" alt="访问次数"/>
  <a href="https://github.com/helGayhub233/BurpSuiteCN/releases"><img src="https://img.shields.io/github/downloads/helGayhub233/BurpSuiteCN/total" alt="下载次数"/></a>
</p>

<img src="https://github.com/helGayhub233/BurpSuiteCN/blob/main/demo.png" />

## 📦 快速开始

1. 将Jar文件放置在程序目录 `mv burpsuiteloader.jar`
2. 在 Burp Suite 安装目录中找到并编辑 `vmoptions.txt`
3. 编辑现有条目或新增条目：

```
--add-opens=java.base/java.lang=ALL-UNNAMED
--add-opens=java.base/java.lang.reflect=ALL-UNNAMED
--add-opens=java.base/java.io=ALL-UNNAMED
--add-opens=java.base/java.util=ALL-UNNAMED
--add-opens=java.base/java.security=ALL-UNNAMED
--enable-native-access=ALL-UNNAMED

-javaagent:burpsuiteloader.jar=loader,chs
```

3. 配置完成后，直接使用以下方式启动：
   - 双击 Burp Suite 应用
   - 启动脚本 / 快捷方式
  
> 注意：为确保`问题定义`字段匹配，建议将程序字体改为: 10

## ⚠️ 免责声明

本项目仅供学习交流使用，请支持正版软件。
<br>
## 📄 License

MIT License
