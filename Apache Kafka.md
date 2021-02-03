## Apache Kafka
* Apache Kafka можно начать со статьи автора Кафки ~~https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying~~
* далее по основам ~~https://learning.oreilly.com/videos/introduction-to-apache/9781491923306/~~ и https://learning.oreilly.com/live-training/courses/kafka-fundamentals/0636920385745/
* разобрать книгу про Apache Kafka ~~https://learning.oreilly.com/library/view/kafka-the-definitive/9781491936153/~~ количество хороших отзывов большое. Есть версия на русском языке. Начало книги не очень понятно написано. Много тумана: мол оно примерно так устроено, а как конкретно пока не скажем. Но во второй половине книги пошла мякотка.
* https://learning.oreilly.com/library/view/kafka-the-definitive/9781492043072/ это вторая редакция(Пока ранний доступ вроде как декабрь 2021 срок)
* разобрать книгу про Apache Kafka Streams ~~https://learning.oreilly.com/library/view/kafka-streams-in/9781617294471/~~ тоже хорошие отзывы. Книга интересная и можно/нужно использовать если попадутся задачи. На hh.ru есть 50 вакансий с таким требоавнием.

* сделать лабы по Apache Kafka:
* https://github.com/gwenshap/kafka-examples это примеры от автора книг по Кафке Gwen (Chen) Shapira

### Почитать
* https://cwiki.apache.org/confluence/display/KAFKA/Kafka+Improvement+Proposals особенно KIP-98
* https://www.confluent.io/blog/journey-to-event-driven-part-1-why-event-first-thinking-changes-everything/

### Exactly Once Delivery
К сожалению, без подготовки по Распределенным системам не получится хорошо понять. Надо почитать Таненбаума и потом вернуться с этого места:
до 0.11 не было EoS. Потом появилось типа EoS продьюсер как сочетание идемпотентного продьюсера и транзакции. по этому нужно почитать https://cwiki.apache.org/confluence/display/KAFKA/KIP-98+-+Exactly+Once+Delivery+and+Transactional+Messaging  и https://cwiki.apache.org/confluence/display/KAFKA/KIP-129%3A+Streams+Exactly-Once+Semantics После 2.5 появилось ещё https://www.confluent.io/blog/simplified-robust-exactly-one-semantics-in-kafka-2-5/ И вообще блог https://www.confluent.io/blog/ интересный. Также на Medium есть интересные статьи, например, https://medium.com/@jaykreps Также https://www.the-paper-trail.org/post/2017-07-28-exactly-not-atomic-broadcast-still-impossible-kafka/ 
* Ржака в самом конце https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/ 
