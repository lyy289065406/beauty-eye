# beauty-eye

> swing 仿 Mac 外观风格构件

------

## 简介

因此构件的官方组织/作者已放弃维护，且在 maven 中央仓库无法下载原版，故有了此项目。

> 原代码仓库为：https://github.com/JackJiang2011/beautyeye

## 使用方式

maven 的 `settings.yml` 配置 sonatype 中央仓库：

```xml
<mirror>
    <id>mvnrepository</id>
    <mirrorOf>mvnrepository</mirrorOf>
    <url>http://mvnrepository.com/</url>
</mirror>

<mirror>
    <id>sonatype</id>
    <mirrorOf>sonatype</mirrorOf>
    <url>https://s01.oss.sonatype.org/</url>
</mirror>
```

项目的 `pom.xml` 配置构件坐标：

```xml
<dependency>
    <groupId>com.exp-blog</groupId>
    <artifactId>beauty-eye</artifactId>
    <version>3.7.0</version>
</dependency>
```


## 相关文档

- [Javadoc](https://lyy289065406.github.io/beauty-eye/)
- [中文](./SOP_ch.md)
- [英文](./SOP_en.md)

