# IRIS Artefacts


### Add useragent-generic-java dependency into maven projects 
#### pom.xml changes

	<repositories>
		<repository>
			<id>mjangid</id>
			<name>iris-repo</name>
			<url>https://github.com/mjangid/iris-repo/raw/master/</url>
		</repository>
	</repositories>


	<dependencies>
		<dependency>
			<groupId>com.temenos.interaction</groupId>
			<artifactId>useragent-generic-java</artifactId>
			<version>0.10.0</version>
			<scope>compile</scope>
		</dependency>
	</dependencies>
