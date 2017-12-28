### macos  aliyun阿里云Maven仓库地址配置

- 创建settings.xml
```
➜    vi /Users/tony/.m2/settings.xml
```

- copy 如下内容

```
<?xml version="1.0" encoding="UTF-8"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
          xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">
  </pluginGroups>
  </proxies>
  <servers>
  </servers>
  <mirrors>
     <mirror>  
      <id>alimaven</id>  
      <name>aliyun maven</name>  
      <url>http://maven.aliyun.com/nexus/content/groups/public/</url>  
      <mirrorOf>central</mirrorOf>          
    </mirror>
  </mirrors>
  <profiles>
  </profiles>
</settings>

```