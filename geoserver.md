## 搭建geoserver

### 初始准备工作

#### geoserver官网下载最新的bin版本及接下来要用到的三个插件

1. geoserver-2.18.0-bin.zip
2. geoserver-2.18.0-wps-plugin.zip
3. geoserver-2.18-SNAPSHOT-mbtiles-plugin.zip
4. geoserver-2.18-SNAPSHOT-vectortiles-plugin.zip

> 解压后的插件jar文件 放到geoserver-2.18.0-bin/webapps/geoserver/WEB-INF/lib目录下
> 
> 之后启动服务 geoserver-2.18.0-bin/bin/start.sh

#### 下载vector mbtiles 矢量地图 [https://openmaptiles.com/](https://openmaptiles.com/)

### 启动geoserver 登录 admin/geoserver
1. 创建工作区
2. 添加数据源。数据存储-添加新的数据存储 - 选择“MBTiles with vector tiles”
3. 添加图层
4. 可以考虑添加图层组 统一管理
5. 图层可以赋予不同的样式style
