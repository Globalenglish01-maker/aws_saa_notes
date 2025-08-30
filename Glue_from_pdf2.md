### 第1-1页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第1页
AWS Glue
Table definitions and ETL
--- 第1页结束 ---

```

### 第2-2页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第2页
What is Glue?
• Serverless discovery and definition
of table definitions and schema
• S3 “data lakes”
• RDS
• Redshift
• DynamoDB
• Most other SQL databases
• Custom ETL jobs
• Trigger-driven, on a schedule, or on
demand
• Fully  managed
--- 第2页结束 ---

```

### 第3-3页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第3页
Glue Crawler / Data Catalog
•
Glue crawler scans data in S3, creates
schema
•
Can run periodically
•
Populates the Glue Data Catalog
•
Stores only table definition
•
Original data stays in S3
•
Once cataloged, you can treat your
unstructured data like it’s structured
•
Redshift Spectrum
•
Athena
•
EMR
•
Quicksight
--- 第3页结束 ---

```

### 第4-4页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第4页
Glue and S3 Partitions
• Glue crawler will extract partitions based on how your S3 data is organized
• Think up front about how you will be querying your data lake in S3
• Example: devices send sensor data every hour
• Do you query primarily by time ranges?
• If so, organize your buckets as yyyy/mm/dd/device
• Do you query primarily by device?
• If so, organize your buckets as device/yyyy/mm/dd
Device 1
Device 2
2018
2019
2018
2019
01
02 … 01
02 …
01
02 … 01
02 …
--- 第4页结束 ---

```

### 第5-5页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第5页
Glue + Hive
•
Hive lets you run SQL-like queries
from EMR
•
The Glue Data Catalog can serve as
a Hive “metastore”
•
You can also import a Hive
metastore into Glue
--- 第5页结束 ---

```

### 第6-6页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第6页
Glue ETL
• Automatic code generation
• Scala or Python
• Encryption
• Server-side (at rest)
• SSL (in transit)
• Can be event-driven
• Can provision additional “DPU’s” (data processing units) to increase
performance of underlying Spark jobs
• Enabling job metrics can help you understand the maximum capacity in DPU’s you
need
• You can plot maximum needed executors vs. maximum allocated executors in the
Glue Console (not CloudWatch!), as well as ETL data movement
• Errors also reported to CloudWatch
• Could tie into SNS for notification
--- 第6页结束 ---

```

### 第7-7页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第7页
Glue ETL
• Transform data, Clean Data, Enrich Data (before doing
analysis)
• Generate ETL code in Python or Scala, you can modify the code
• Can provide your own Spark or PySpark scripts
• Target can be S3, JDBC (RDS, Redshift), or in Glue Data Catalog
• Fully managed, cost effective, pay only for the resources
consumed
• Jobs are run on a serverless Spark platform
• Glue Scheduler to schedule the jobs
• Glue Triggers to automate job runs based on “events”
--- 第7页结束 ---

```

### 第8-8页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第8页
Glue ETL: The DynamicFrame
• A DynamicFrame is a collection of DynamicRecords
• DynamicRecords are self-describing, have a schema
• Very much like a Spark DataFrame, but with more ETL stuff
• Scala and Python APIs
val pushdownEvents = glueContext.getCatalogSource(
database = "githubarchive_month", tableName = "data“)
val projectedEvents = pushdownEvents.applyMapping(Seq(
("id", "string", "id", "long"), ("type", "string", "type",
"string"), ("actor.login", "string", "actor", "string"),
("repo.name", "string", "repo", "string"),
("payload.action", "string", "action", "string"),
("org.login", "string", "org", "string"), ("year",
"string", "year", "int"), ("month", "string", "month",
"int"), ("day", "string", "day", "int") ))
ID
Year
Month…
DynamicRecord
ID
Year
Month…
DynamicRecord
ID
Year
Month…
DynamicRecord
DynamicFrame
…
--- 第8页结束 ---

```

### 第9-9页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第9页
Glue ETL - Transformations
• Bundled Transformations:
• DropFields, DropNullFields – remove (null) fields
• Filter – specify a function to filter records
• Join – to enrich data
• Map - add fields, delete fields, perform external lookups
• Machine Learning Transformations:
• FindMatches ML: identify duplicate or matching records in your dataset,
even when the records do not have a common unique identifier and no fields
match exactly.
• Format conversions: CSV, JSON, Avro, Parquet, ORC, XML
• Apache Spark transformations (example: K-Means)
• Can convert between Spark DataFrame and Glue DynamicFrame
--- 第9页结束 ---

```

### 第10-10页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第10页
Glue ETL: ResolveChoice
•
Deals with ambiguities in a DynamicFrame and returns a new one
•
For example, two fields with the same name.
•
make_cols: creates a new column for each type
•
price_double, price_string
•
cast: casts all values to specified type
•
make_struct: Creates a structure that contains each data type
•
project: Projects every type to a given type, for example project:string
df1 = df.resolveChoice(choice = "make_cols")
df2 = df.resolveChoice(specs = [("myList[].price",
"make_struct"), ("columnA", "cast:double")])
"myList": [ { "price": 100.00 }, { "price": "$100.00" } ]
--- 第10页结束 ---

```

### 第11-11页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第11页
Glue ETL: Modifying the Data Catalog
• ETL scripts can update your schema and partitions if
necessary
• Adding new partitions
• Re-run the crawler, or
• Have the script use enableUpdateCatalog and
partitionKeys options
• Updating table schema
• Re-run the crawler, or
• Use enableUpdateCatalog / updateBehavior from script
• Creating new tables
• enableUpdateCatalog / updateBehavior with setCatalogInfo
• Restrictions
• S3 only
• Json, csv, avro, parquet only
• Parquet requires special code
• Nested schemas are not supported
--- 第11页结束 ---

```

### 第12-12页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第12页
AWS Glue Development Endpoints
• Develop ETL scripts using a notebook
• Then create an ETL job that runs your
script (using Spark and Glue)
• Endpoint is in a VPC controlled by
security groups, connect via:
• Apache Zeppelin on your local machine
• Zeppelin notebook server on EC2 (via
Glue console)
• SageMaker notebook
• Terminal window
• PyCharm professional edition
• Use Elastic IP’s to access a private
endpoint address
--- 第12页结束 ---

```

### 第13-13页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第13页
Running Glue jobs
• Time-based schedules (cron style)
• Job bookmarks
• Persists state from the job run
• Prevents reprocessing of old data
• Allows you to process new data only when re-running on a
schedule
• Works with S3 sources in a variety of formats
• Works with relational databases via JDBC (if PK’s are in
sequential order)
• Only handles new rows, not updated rows
• CloudWatch Events
• Fire off a Lambda function or SNS notification when ETL
succeeds or fails
• Invoke EC2 run, send event to Kinesis, activate a Step
Function
--- 第13页结束 ---

```

### 第14-14页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第14页
Glue cost model
• Billed by the second for crawler
and ETL jobs
• First million objects stored and
accesses are free for the Glue
Data Catalog
• Development endpoints for
developing ETL code charged by
the minute
--- 第14页结束 ---

```

### 第15-15页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第15页
Glue Anti-patterns
• Multiple ETL engines
• Glue ETL is based on Spark
• If you want to use other engines (Hive,
Pig, etc) Data Pipeline EMR would be
a better fit.
--- 第15页结束 ---

```

### 第16-16页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第16页
No longer an anti-pattern: streaming
• As of April 2020, Glue ETL supports serverless streaming ETL
• Consumes from Kinesis or Kafka
• Clean & transform in-flight
• Store results into S3 or other data stores
• Runs on Apache Spark Structured Streaming
--- 第16页结束 ---

```

### 第17-17页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第17页
AWS Glue Studio
• Visual interface for ETL
workflows
• Visual job editor
• Create DAG’s for complex
workflows
• Sources include S3, Kinesis,
Kafka, JDBC
• Transform / sample / join data
• Target to S3 or Glue Data
Catalog
• Support partitioning
• Visual job dashboard
• Overviews, status, run times
--- 第17页结束 ---

```

### 第18-18页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第18页
AWS Glue Data Quality
• Data quality rules may be created
manually or recommended
automatically
• Integrates into Glue jobs
• Uses Data Quality Definition
Language (DQDL)
• Results can be used to fail the job,
or just be reported to CloudWatch
--- 第18页结束 ---

```

### 第19-19页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第19页
AWS Glue Data Quality
--- 第19页结束 ---

```

### 第20-20页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第20页
AWS Glue DataBrew
• A visual data preparation tool
• UI for pre-processing large data sets
• Input from S3, data warehouse, or database
• Output to S3
• Over 250 ready-made transformations
• You create “recipes” of transformations that can be
saved as jobs within a larger project
• May define data quality rules
• May create datasets with custom SQL from Redshift
and Snowflake
• Security
• Can integrate with KMS (with customer master keys only)
• SSL in transit
• IAM can restrict who can do what
• CloudWatch & CloudTrail
{
"RecipeAction": {
"Operation": "NEST_TO_MAP",
"Parameters": {
"sourceColumns":
"[\"age\",\"weight_kg\",\"height_cm\"]",
"targetColumn": "columnName",
"removeSourceColumns": "true"
}
}
}
Example: convert selected columns to key-value pairs
--- 第20页结束 ---

```

### 第21-21页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第21页
Handling Personally Identifiable
Information (PII) in DataBrew
Transformations
• Enable PII statistics in a DataBrew profile
job to identify PII
• Substitution
(REPLACE_WITH_RANDOM…)
• Shuffling (SHUFFLE_ROWS)
• Deterministic encryption
(DETERMINISTIC_ENCRYPT)
• Probabilistic encryption (ENCRYPT)
• Decryption (DECRYPT)
• Nulling out or deletion (DELETE)
• Masking out (MASK_CUSTOM, _DATE,
_DELIMITER, _RANGE)
• Hashing (CRYPTOGRAPHIC_HASH)
--- 第21页结束 ---

```

### 第22-22页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第22页
Glue Workflows
• Design multi-job, multi-crawler ETL processes run together
• Create from AWS Glue blueprint, from the console, or API
• This is only for orchestrating complex ETL operations using
Glue
--- 第22页结束 ---

```

### 第23-23页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第23页
Glue Workflow Triggers
• Triggers within workflows start jobs or
crawlers
• Or can be fired when jobs or crawlers
complete
• Schedule
• Based on a cron expression
• On demand
• EventBridge events
• Start on single event or batch of events
• For example, arrival of a new object in S3
• Optional batch conditions
• Batch size (number of events)
• Batch window (within X seconds, default is 15
min)
--- 第23页结束 ---

```

### 第24-24页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第24页
AWS Lake Formation
• “Makes it easy to set up a secure data lake
in days”
• Loading data & monitoring data flows
• Setting up partitions
• Encryption & managing keys
• Defining transformation jobs & monitoring
them
• Access control
• Auditing
• Built on top of Glue
--- 第24页结束 ---

```

### 第25-25页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第25页
AWS Lake Formation
S3 Data Lake
S3
RDBMS
NoSQL
Lake Formation
Crawlers, ETL, data catalog,
security, ACL, cleaning,
transformations (including Parquet
& ORC) – basically anything Glue
can do
Athena
Redshift
EMR
On-premises or AWS
--- 第25页结束 ---

```

### 第26-26页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第26页
AWS Lake Formation: Pricing
• No cost for Lake Formation itself
• But underlying services incur
charges
• Glue
• S3
• EMR
• Athena
• Redshift
--- 第26页结束 ---

```

### 第27-27页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第27页
AWS Lake
Formation:
Building a
Data Lake
Create an IAM user for
Data Analyst
Create AWS Glue
connection to your data
source(s)
Create S3 bucket for the
lake
Register the S3 path in
Lake Formation, grant
permissions
Create database in Lake
Formation for data
catalog, grant
permissions
Use a blueprint for a
workflow (ie, Database
snapshot)
Run the workflow
Grant SELECT
permissions to whoever
needs to read it (Athena,
Redshift Spectrum, etc)
--- 第27页结束 ---

```

### 第28-28页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第28页
AWS Lake
Formation:
The Finer
Points
• Cross-account Lake Formation permission
• Recipient must be set up as a data lake
administrator
• Can use AWS Resource Access Manager
for accounts external to your organization
• IAM permissions for cross-account access
• Lake Formation does not support manifests in
Athena or Redshift queries
• IAM permissions on the KMS encryption key
are needed for encrypted data catalogs in
Lake Formation
• IAM permissions needed to create blueprints
and workflows
--- 第28页结束 ---

```

### 第29-29页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第29页
Data Permissions
in Lake Formation
• Can tie to IAM users/roles,
SAML, or external AWS accounts
• Can use policy tags on
databases, tables, or columns
• Can select specific permissions
for tables or columns
--- 第29页结束 ---

```

### 第30-30页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第30页
Data Filters in Lake Formation
• Column, row, or cell-level security
• Apply when granting SELECT
permission on tables
• “All columns” + row filter = row-
level security
• “All rows” + specific columns =
column-level security
• Specific columns + specific rows =
cell-level security
• Create filters via the console (seen
here) or via
CreateDataCellsFilter API.
--- 第30页结束 ---

```

### 第31-31页

```
你将接收到一页英语原文，作为小白，我完全看不懂记不住啊，怎么办？
解释时，先提供如下内容
1. 格式化好的原文，
2. 格式化后原文及其逐句对应的国际音标
3. 原文的中文翻译，
4. 缩写详解，
5. 英语关键词详解，
6. 速览版（30 秒内能读完）
🔑 本页重点：一句话总结
📌 关键词：核心术语
🎯 学习提示：最可能出现在考试里的考点
7. 再通俗易懂的解释一遍，
8. 小白也懂的语言再解释一遍，
9. 提供小结，
10. 记忆口诀。
英语原文内容如下：

🟩 第31页
Amazon Athena
Serverless interactive queries of S3 data
--- 第31页结束 ---

```