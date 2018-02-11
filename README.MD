# In development, please do not use for production environment.

# stable version
NONE

# 项目目标
简约高效的分布式数据采集器，更加适用于私有化部署和小型定制化业务的开发。[目标:阶段1](docs/target_1.md)

主要面向精准化数据采集，基于爬虫的理念。
但是支持对数据抽取工作的插件化操作，侧重对ELT(Extract, Load, Transform)数据处理业务的支持。
(相对于ETL)

加强适应性，本系统依赖的第三方系统(Redis kafka等)均可以按照业务的规模等抽换或禁用。

##