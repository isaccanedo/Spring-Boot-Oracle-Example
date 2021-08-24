# Spring Boot Oracle Example

* Para executar este exemplo, você precisará baixar e instalar o driver Oracle JDBC 6 (ojdbc6.jar) do site da Oracle para
   Driver Oracle 11g ou Oracle JDBC 7 (ojdbc7.jar) para Oracle 12c.
* You can install the Oracle Jar into your local Maven repsository by opening terminal, going to the folder where you have downloaded the
  jar and using this below command:

  mvn install:install-file -Dfile=ojdbc6.jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -Dpackaging=jar
