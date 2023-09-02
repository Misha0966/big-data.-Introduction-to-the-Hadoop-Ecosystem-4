Урок 4. Hive & HUE

Литература:

Общие концепции YARN
https://blog.cloudera.com/apache-hadoop-yarn-concepts-and-applications/
Управление ресурсами
https://towardsdatascience.com/schedulers-in-yarn-concepts-to-configurations-5dd7ced6c214
Map reduce:
https://habr.com/ru/company/dca/blog/267361/

Опробовать запуски map-reduce задач для кластера используя hadoop-mapreduce-examples.jar.
Чтобы увидеть полный список нужно выполнить yarn jar $YARN_EXAMPLES/hadoop-mapreduce-
examples.jar без параметров. (Там, например, wordcount тоже есть)

Выполнить любую задачу включенную в этот JAR
Найти свою задачи в интерфейсе Cloudera Manager

Пример:
YARN_EXAMPLES=/opt/cloudera/parcels/CDH-5.16.2-1.cdh5.16.2.p0.8/lib/hadoop-mapreduce
yarn jar $YARN_EXAMPLES/hadoop-mapreduce-examples.jar pi 32 20000

Задачи на собеседование (про YARN спрашивают редко, поэтому со звёздочкой):
*Что такое YARN?
*Почему задачи на YARN нестабильны?
Почему Map Reduce долго выполняется?
Почему Map Reduce не выполняется?
*Где хранится результат выполнения Map Reduce?
