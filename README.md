# Spring Boot Oracle Example

* Para executar este exemplo, você precisará baixar e instalar o driver Oracle JDBC 6 (ojdbc6.jar) do site da Oracle para
   Driver Oracle 11g ou Oracle JDBC 7 (ojdbc7.jar) para Oracle 12c.
* Você pode instalar o Oracle Jar em seu repositório Maven local abrindo o terminal, indo para a pasta onde você baixou o
  jar e usando o comando abaixo:

  mvn install:install-file -Dfile=ojdbc6.jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0 -Dpackaging=jar
