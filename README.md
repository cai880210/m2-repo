m2-repo
========

Simple Maven repository for eu.impact_project artifacts .

To use add:

```xml
  <repositories>
  	<repository>
		<id>impact</id>
		<url>https://github.com/impactcentre/m2-repo/raw/master/releases</url>
	</repository>
  </repositories>
```

to your pom.xml and reference the projects as:

```xml
<dependency>
  <groupId>eu.impact_project.iif.ws</groupId>
	<artifactId>generic-soap-client</artifactId>
	<version>0.5.0</version>
</dependency>
```


