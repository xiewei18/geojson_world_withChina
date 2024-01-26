# 项目说明 About

全球国家级行政边界&amp;中国分层次行政区边界。

Worldwide country-level geojson dataset along with Hierarchical administrative boundary within China.

本项目是为了为中国区域及相关学术研究提供方便可用的统一行政边界信息（包括嵌套中国国内行政边界的世界地图）。

This project aims to provide a convenient and usable unified administrative boundary information for the China region and related academic research (including a world map with nested Chinese domestic administrative boundaries).

本项目是 [CTAMap](https://www.ctamap.org) 项目的一部分。

This is part of the [CTAMap](https://www.ctamap.org) project.

提供的行政边界信息包含中英文行政区简称、全称以及ISO代码，便于匹配研究数据。

The provided administrative boundary information includes the short and full names of the administrative regions in both Chinese and English, as well as the ISO codes, which are convenient for matching research data.

## 数据格式 Data Format

数据以GeoJSON格式提供，可以使用任何支持GeoJSON的GIS软件或库进行读取和处理。

The data is provided in GeoJSON format, which can be read and processed by any GIS software or library that supports GeoJSON.

## 使用数据 Using the Data

这些数据可以方便地与R或Python等编程语言进行交互，同样适用于在线可视化平台。

The data can be easily interacted with programming languages such as R or Python, as well as web-based visualization platforms like Echarts. 

## 元数据 Metadata

| Field Name | Field Type | Description (EN) | 描述 (CN) |
| ---------- | ---------- | ---------------- | --------- |
| OBJECTID   | integer    | Object ID        | ID 编号    |
| name       | string     | Short name in English | 英文简称  |
| name_full  | string     | Full name in English | 英文全称  |
| SOC        | string     | SOC code      | SOC 国家代码  |
| name_chn   | string     | Short name in Chinese | 中文简称  |
| name_chn_full | string  | Full name in Chinese | 中文全称  |
| iso_a2     | string     | ISO 2-letter code | ISO 2字母代码 |
| iso_a3     | string     | ISO 3-letter code | ISO 3字母代码 |
| iso_n3     | string     | ISO 3-digit code | ISO 3数字代码 |
| geometry   | object     | Geometry information, including type and coordinates | 几何信息，包含类型和坐标 |

## 更新频率 Update Frequency

数据将根据源数据的更新情况进行更新，具体更新频率请参考源数据仓库。

The data will be updated according to the update situation of the source data. For the specific update frequency, please refer to the source data repository.

## 致谢及参考资料 Aknowledgement & References

本项目参考了以下资料整理而成，感谢相关作者的付出与努力：

This project was compiled based on the following resources. We appreciate the dedication and hard work of the respective authors:

- [全球国家行政边界数据](https://www.resdc.cn/data.aspx?DATAID=205)
- [world-geo-json-zh](https://github.com/Surbowl/world-geo-json-zh)
- [DataV.GeoAtlas](https://datav.aliyun.com/portal/school/atlas)
- [Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China)
