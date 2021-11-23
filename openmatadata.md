## OpenMeatadata

OpenMeatadata意为开放元数据.它是一个开放标准,具有中心化元数据存储,可以端到端地统一你所有数据资产,以实现数据发现,用户协作和工具协同.

![open-metadata 实现架构](https://docs.open-metadata.org/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FLpcRqQJ8rFWtdxuc4yv7%2Fuploads%2Fgit-blob-a15b461c6bcec34edb7d134bd5d514355dd20e9a%2Fopenmetadata-overview%20(1).png?alt=media)

OpenMeatadata组成部分:

Metadata schemas:Open Metadata标准的基础.通过类型,实体和实体关系的结构(schema)为元数据定义核心抽象和词汇.

Metadata store:存储连接数据资产,用户和工具生成元数据的元数据图表.

Metadata APIs: 针对用户界面和工具,系统,服务的集成,基于结构(schema)来生成和消费元数据.通过结构(schema)数据对外提供服务.

Ingestion framework: 一个用于集成工具和提取元数据到元数据存储的可插拔框架.提取框架已经支持流行数据仓库:BigQuery, Snowflake, Amazon Redshift,和 Apache Hive,以及MySQL, Postgres, Oracle, and MSSQL数据库.

OpenMetadata User Interface: 用于用户基于所有数据发现和合作的集中场所.











