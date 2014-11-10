NPI Maven Repository
====================

Uso de dependências do repositório Maven do NPI no seu projeto
--------------------------------------------------------------

A seguir um exemplo de uso da dependência *npi-core-api* do repositório Maven no NPI. 
Basta configurar a API como dependência do seu projeto no arquivo pom.xml:

```xml
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  ...
  <!-- In Project repository -->
  <repositories>
    <repository>
      <id>npi-mvn-repo</id>
      <url>http://npi-ufc-qxd.github.io/npi-mvn-repo/</url>
    </repository>
  </repositories>
  ...
  <dependencies>
    ...
    <dependency>
      <groupId>br.ufc.quixada.npi</groupId>
      <artifactId>npi-core-api</artifactId>
      <version>0.0.8</version>
    </dependency>
    ...
  </dependencies>
  ...
</project>
```
