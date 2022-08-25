# Learning-Path
Забавный РоадМап: https://github.com/datastacktv/data-engineer-roadmap

## Статейки
1. ~~https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying~~ тяжело написанная статья. 
2. ~~https://highlyscalable.wordpress.com/2013/08/20/in-stream-big-data-processing/~~ неплохо, но в 2020 не очень актуально.
3. https://engineering.linkedin.com/datafu/datafus-hourglass-incremental-data-processing-hadoop
4. ~~https://queue.acm.org/detail.cfm?id=2745385~~ There is No Now Problems with simultaneity in distributed systems
5. ~~http://nathanmarz.com/blog/how-to-beat-the-cap-theorem.html~~ How to beat the CAP theorem. Забавно, но в 2021 году читать про разделение аналитики реального времени и батч процессинг - кажется  естественным. Интересны проблемы которые автор в конце статьи описывает как то, что ещё нужно решить.
6. ~~https://www.oreilly.com/radar/questioning-the-lambda-architecture/~~ Questioning the Lambda Architecture. The Lambda Architecture has its merits, but alternatives are worth exploring.
7. ~~https://www.oreilly.com/content/why-local-state-is-a-fundamental-primitive-in-stream-processing/~~
8. ~~https://martinfowler.com/articles/201701-event-driven.html What do you mean by “Event-Driven”?~~ Есть аналогичное видео https://youtu.be/STKCRSUsyP0
9. https://www.confluent.io/blog/event-streaming-new-big-thing-finance Is Event Streaming the New Big Thing for Finance?
10. https://www.the-paper-trail.org/post/2014-06-25-the-elephant-was-a-trojan-horse-on-the-death-of-map-reduce-at-google/
11. Сборник ссылок: https://girlincomputerscience.blogspot.com/2017/11/bigdata-history.html
12. Dataflow https://research.google.com/pubs/archive/43864.pdf
13. ~~https://engineering.linkedin.com/blog/2020/lambda-to-lambda-less-architecture~~ очень похоже на реальный кейс. Надо ещё разок посмотреть чуть попозже
14. https://www.confluent.io/blog/running-kafka-at-scale-at-pinterest/

## Основы
* ~~прочитать Таненбаум: Компьютерные сети~~
* ~~прочитать Таненбаум: Архитектура компьютера~~

## Cloud
* ~~получить GCP Data Engineer~~ сделано) https://www.credential.net/c2e98f34-1998-45a2-9f59-485e8fcdcb40?key=11bf720a7aaa0336277884c77662a4b8287e30e031840543710055941c6f6715 
* получить GCP Cloud Architect
* ~~пройти курс по MS Azure что-нибудь вроде https://learning.oreilly.com/videos/exam-az-900-microsoft/9780137307005/~~ не могу сказать, что интересный курс. Если ты уже знаком с облаками, то лучше не смотреть. Много воды и мало конкретики.
* пройти курс по MS Azure https://learning.oreilly.com/library/view/microsoft-certified-azure/9781264268375/
* ~~разобрать книгу https://learning.oreilly.com/library/view/hands-on-azure-functions/9781484271223/~~ хорошая книга с примерами. для начала работы за глаза и за уши. Для чего-то более тонкого может не хватить. Видимо для деталей нужно курить оффициальную документацию.
* посмотреть чем Azure отличается от GCP
* ~~посмотреть https://learning.oreilly.com/live-events/multi-cloud-comparison-aws-azure-and-google-cloud/0636920414391/0636920068927/~~ не стоит смотреть если у тебя есть хоть какой-нибудь опыт. Вообще курсы/видео этого челика стоит не трогать. Что по Хадуп/Спарк что по облакам он гонит тривиальные вещи и очень тянет время. Лучше прочитать/посмотреть что-нибудь другое

## Containers
* ~~docker: освоить книжку https://learning.oreilly.com/library/view/docker-deep-dive/9781800565135/~~ не плохо, для начала хорошо. Потом документацию и Медиум отдельные статейки и будет совсем хорошо.
* Kubernetes: https://learning.oreilly.com/library/view/kubernetes-in-action/9781617293726/ и обязательно https://learning.oreilly.com/library/view/networking-and-kubernetes/9781492081647/
* ~~начать использовать AKS в продакшене~~ осталось теорию подтянуть. освоить https://learning.oreilly.com/library/view/hands-on-kubernetes-on/9781801079945/

#### DB
* прочитать Дейт SQL и реляционная теория
* ~~прочитать Database System Concepts -  https://www.db-book.com/db6/index.html~~
* прочитать Database System Concepts -  https://www.db-book.com/db7/index.html
* прочитать Database Internals https://learning.oreilly.com/library/view/database-internals/9781492040330/
#### OS
* ~~прочитать Таненбаум: Современные операционные системы~~ слишком высокоуровневая теория для моих задач, но интересно. Если придется копаться внутри ОС, то однозначно надо читать.
#### Distributed Systems
* прочитать Таненбаум: Distributed Systems: Tanenbaum (2017)
* https://www.the-paper-trail.org/post/2008-08-13-a-brief-tour-of-flp-impossibility/ A Brief Tour of FLP Impossibility
* https://www.the-paper-trail.org/post/2012-03-25-flp-and-cap-arent-the-same-thing/ FLP and CAP aren't the same thing
* ~~Разобрать книгу Architecting Modern Data Platforms: A Guide to Enterprise Hadoop at Scale https://www.amazon.com/Architecting-Modern-Data-Platforms-Enterprise/dp/149196927X~~ эта книга как сборник практик. очень мало теории. если есть теория и нужно знать что и как можно сделать с Хадуп, то читать. Но есть мнение, что частично устарела уже.
* Забавно в самом конце https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/ 

#### Other
* ~~пройти вводный курс https://learning.oreilly.com/live-training/courses/hands-on-introduction-to-oauth-20/0636920365303/~~ хороший старт для применения.Если уже прочитал Таненбаума. В данном курсе уже есть практика
* ~~прочитать книгу https://www.amazon.com/Effective-DevOps-Building-Collaboration-Affinity/dp/1491926309~~ неплохая книга. Кника о том, что правильная команда - все, а инструменты - вторично по сравнению с командой. Действительно нужно перечитывать с некоторой периодичностью. Похоже на попурри литературы работы с командой и между командами.
* почитать про балансировщики: nginx, haproxy, envoy, zuul, traefik
* почитать про istio
* посмотреть на Apache Calcite https://calcite.apache.org/

## Messages, Events, Queues and so on
* ~~разобрать спецификацию JMS 1.1/JMS 2.0 https://klvufg.wordpress.com/2018/11/29/jms-1-1/~~
* ~~прочитать книгу про ActiveMQ: https://www.manning.com/books/activemq-in-action~~
* ~~разобрать протокол AMQP https://klvufg.wordpress.com/2019/05/22/rabbitmq-amqp-0-9-1/~~
* ~~разобрать книку https://www.manning.com/books/streaming-data~~ офигенная книжка. Очень понравилась
* разобрать книгу https://en.wikipedia.org/wiki/Enterprise_Integration_Patterns 
* ~~пройти вводный тренинг https://learning.oreilly.com/live-training/courses/mastering-patterns-in-event-driven-architecture/0636920440239/~~
* ~~пройти вводный тренинг https://learning.oreilly.com/videos/distributed-systems-in/9781491924914/~~
* прочитать книгу про Apache Pulsar
* сделать лабы по Apache Pulsar
* посмотрть NATS
* пройти вводный курс https://learning.oreilly.com/live-training/courses/spark-30-first-steps/0636920458197/
* прочитать книгу про Apache Spark
* сделать лабы по Apache Spark 
* прочитать книгу про Apache Hadoop
* сделать лабы по Apache Hadoop
* прочитать книгу про Apache Gobblin
* сделать лабы по Apache Gobblin 
* https://github.com/apache/incubator-gobblin
* прочитать книгу про Apache Samza
* сделать лабы по Apache Samza
* прочитать книгу про Apache Flum
* сделать лабы по Apache Flum
* разобрать книгу https://learning.oreilly.com/library/view/data-pipelines-with/9781617296901/
* прочитать книгу про Apache NiFi
* сделать лабы по Apache NiFi
* что пишет один из авторов НиФи про цели проекта и его видение проекта https://www.reddit.com/r/bigdata/comments/80mprc/apache_nifi_vs_gobblin_vs_others/
* прочитать книгу про Apache Storm
* сделать лабы по Apache Storm
* прочитать книгу про Apache Cassandra
* сделать лабы по Apache Cassandra
* прочитать книгу про Apache Flink
* сделать лабы по Apache Flink
* прочитать книгу про Apache Beam
* сделать лабы по Apache Beam
* ~~Разобрать книгу Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing https://www.amazon.com/Streaming-Systems-Where-Large-Scale-Processing/dp/1491983876~~ книга отличная. Примеры на Apache Beam и Apache Calcite. Пришлось читать 2 раза чтобы, как мне сейчас кажется, понять некоторые мысли достаточно глубоко. О чем эта книга отлично написано на странице x в самом низу 3 пункта: 1. Теория стримов и таблиц и как они между собой связаны 2. time-varying relations 3. распределенные системы это очень крутая штука и чем больше в них разбираешься тем становится очевиднее, сколько тяжелой работы они снимают с разработчиков.

* разобрать Designing Data-Intensive Applications https://dataintensive.net/ офигенная книжка. Очень понравилась!!!

## ETL
Airflow vs. Luigi vs. Argo vs. MLFlow vs. KubeFlow vs. Perfect vs. Dragster

## AWS
* разобрать книгу Learning Amazon Web Services (AWS): A Hands-On Guide to the Fundamentals of AWS Cloud 
* получить сертифиацию AWS Developer Associate
* получить сертифиацию AWS Solution Architect Associate

## Architecture
* ~~пройти вводный курс https://learning.oreilly.com/live-training/courses/architecture-for-continuous-delivery/0636920254331/~~ зачетный курс. Нил Форд - крутой)
* ~~пройти вводный курс https://learning.oreilly.com/live-training/courses/solid-principles-of-object-oriented-and-agile-design/0636920239789/~~ Дядюшка Боб рулит!
* разобрать книгу https://learning.oreilly.com/library/view/fundamentals-of-software/9781492043447/
* прочитать книгу https://www.litres.ru/kris-richardson-2184/mikroservisy-patterny-razrabotki-i-refaktori-50445630/

## Tools
* ~~начать использовать JFrog Artifactory в продакшене~~

## DevOPs
* ~~пройти курс по Azure DevOps https://learning.oreilly.com/videos/azure-devops-and/9781804618660/~~ нормальный верхнеуровневый вводный курс. Крупными блоками рассказывают что можно сделать WYSTYG. Про YAML pipelines рассказывают только что так можно. Ни ссылки на документацию ни разбор какого-нибудь пайплайна. На 3-ку.

