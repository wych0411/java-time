# java-time
java.time package for java8

在Java 8之前，所有关于时间和日期的API都存在各种使用方面的缺陷，主要有：
1. java.util.Date和java.util.Calendar类易用性差，不支持时区，而且它们都不是线程安全的。
2. 用于格式化日期的抽象类DateFormat及其实现SimpleDateFormat被放在java.text包中，而且也不是线程安全的。
3. 对日期的计算方式繁琐，而且容易出错。因为月份是从0开始的，从Calendar中获取的月份需要+1才能表示正确的月份。

Java 8中引入了新的日期api，是标准的JSR-310规范的实现，与开源的Joda-Time日期处理框架类似。

Java 8的日期和时间类包括LocalDate、LocalTime、Instant、Duration以及Period，这些类都包含在java.time包中。
