# BurpSuiteCN 汉化加载器

<p align="center">
  <img src="https://img.shields.io/badge/Java-21+-orange.svg" alt="技术栈"/>
  <img src="https://img.shields.io/badge/Burp-2025.x-purple.svg" alt="支持版本"/>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=helGayhub233.BurpSuiteCN" alt="访问次数"/>
  <a href="https://github.com/helGayhub233/BurpSuiteCN/releases"><img src="https://img.shields.io/github/downloads/helGayhub233/BurpSuiteCN/total" alt="下载次数"/></a>
</p>

## 📦 快速开始

### 方式一：一键启动（推荐）

```bash
java -jar burpsuiteloader.jar
```

启动后会显示 Keygen 界面，可生成许可证密钥。

### 方式二：JavaAgent 方式

```bash
# 激活 + 汉化
java -javaagent:burpsuiteloader.jar=loader,chs -jar burpsuite_pro.jar

# 仅激活
java -javaagent:burpsuiteloader.jar=loader -jar burpsuite_pro.jar

# 仅汉化
java -javaagent:burpsuiteloader.jar=chs -jar burpsuite_pro.jar
```

---


## ⚠️ 免责声明

本项目仅供学习交流使用，请支持正版软件。

---

## 📄 License

MIT License
