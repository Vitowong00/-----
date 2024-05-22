# 去搜 --- 一站式信息搜索

> by vito wang

## 项目介绍

基于 Spring Boot 和 Elastic Stack 的综合信息搜索平台，旨在提升用户的搜索体验，是一个一站式信息
聚合搜索平台，其主要功能是可以在同一个页面集中搜索出不同来源、不同类型的内容，比如通过关键
词“Java”去搜索在文章块、图片块、用户块等中都可以搜索。

对用户来说：提升用户的检索效率、提升用户体验

对企业来说：无需针对每一个项目都去开发一个搜索功能，当有新的内容、新的网站时，可以复用同一套搜索系统，提升开发效率

## 技术栈

### 前端

- Vue
- Ant Design Vue
- Lodash

### 后端

- SpringBoot
- MySQL
- ElasticSearch（Elastic Stack）搜索引擎
- 数据抓取
- 数据同步
  - logstash
  - Canal
