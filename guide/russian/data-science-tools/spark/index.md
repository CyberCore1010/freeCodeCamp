---
title: Spark
localeTitle: искра
---
## искра

[Spark](http://spark.apache.org/) - это быстрая и общая кластерная вычислительная система для больших данных. Он предоставляет API-интерфейсы высокого уровня в Scala, Java, Python и R и оптимизированный механизм, который поддерживает общие вычислительные графики для анализа данных. Он также поддерживает богатый набор инструментов более высокого уровня, включая Spark SQL для SQL и DataFrames, MLlib для машинного обучения, GraphX ​​для обработки графов и Spark Streaming для обработки потоков.

## Основные особенности

Spark 2.0 имеет много новых возможностей:

*   Собственный источник данных CSV, основанный на модуле искры-CSV Databricks
*   Управление памятью кучи для кэширования и выполнения во время выполнения
*   Поддержка буксировки стиля улья
*   Приблизительная сводная статистика с использованием эскизов, включая приблизительный квантиль, фильтр Блума и эскиз счет-мин.

## Как это используется для Data Science

Spark стал стандартным инструментом во многих инструментальных ящиках данных. Благодаря гибкости в выборе API любой программист может работать с Spark на своем предпочтительном языке. Как отметил [Клаудера](https://blog.cloudera.com/blog/2014/03/why-apache-spark-is-a-crossover-hit-for-data-scientists) , Spark завоевал популярность по многим причинам:

*   Будучи Scala-based, Spark внедряется в любую операционную систему на основе JVM, но также может быть интерактивно использована в REPL таким образом, чтобы она была знакома пользователям R и Python.
*   Для Java-программистов Scala по-прежнему представляет собой кривую обучения. Но, по крайней мере, любая библиотека Java может использоваться из Scala. Абстракция Spark's RDD (Resilient Distributed Dataset) похожа на Crol's PCollection, которая оказалась полезной абстракцией в Hadoop, которая уже будет знакома разработчикам Crunch. (Хруст может даже использоваться поверх Spark.)
*   Spark имитирует API коллекций Scala и функциональный стиль, который является благом для разработчиков Java и Scala, но также немного знакомы разработчикам из Python. Scala также является убедительным выбором для статистических вычислений.
*   Сам искры и Скала под ним не являются специфическими для машинного обучения. Они предоставляют API-интерфейсы, поддерживающие связанные задачи, такие как доступ к данным, ETL и интеграция. Как и в случае с Python, вся эта научная цепочка может быть реализована в рамках этой парадигмы, а не только подгонки модели и анализа.
*   Код, который реализован в среде REPL, может использоваться в основном как-в рабочем контексте.
*   Операции с данными прозрачно распределяются по кластеру, даже когда вы печатаете.

#### Больше информации

*   [Страница Spark Github](https://github.com/apache/spark)
*   [Википедия](https://en.wikipedia.org/wiki/Apache_Spark)