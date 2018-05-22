# mule4-importable-mule-configs
This is a Maven (Java) project that contains two test Mule configuration files. This is used in conjunction with the mule4-importing-mule-configs project to demonstrate how to import Mule config files from an external (jar file) source.

Build this project with mvn clean install and the jar file can then be imported into a Mule project using the import component.

Don't forget to define this jar file as a dependency in the Mule project:

```
<dependency>
	<groupId>org.mule.consulting.importable</groupId>
	<artifactId>mule4-importable-mule-config-files</artifactId>
	<version>1.0.0</version>
</dependency>

```
