# mnt-homeworks-03-cicd
Домашнее задание к занятию 9 «Процессы CI/CD»

1. Создал две виртуальные машины
2. Установил при помощи ansible необходимое ПО
3. Успешно проверил и исправил код в SonarQube
![alt text](image.png)

4. Дважды загрузил артефакт в Nexus

<metadata modelVersion="1.1.0">
<groupId>netology</groupId>
<artifactId>java</artifactId>
<versioning>
<latest>8_282</latest>
<release>8_282</release>
<versions>
<version>8_102</version>
<version>8_282</version>
</versions>
<lastUpdated>20240407182827</lastUpdated>
</versioning>
</metadata>

5. pom.xml
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>

  <groupId>com.netology.app</groupId>
  <artifactId>simple-app</artifactId>
  <version>1.0-SNAPSHOT</version>
   <repositories>
    <repository>
      <id>my-repo</id>
      <name>maven-public</name>
      <url>http://62.84.116.110:8081/repository/maven-public/</url>
    </repository>
  </repositories>
  <dependencies>
   <dependency>
      <groupId>netology</groupId>
      <artifactId>our-dependency</artifactId>
      <version>8_1022</version>
      <classifier>distrib</classifier>
      <type>jar</type>
    </dependency>
  </dependencies>
</project>




