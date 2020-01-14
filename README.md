# dv-customer-fatjar

This is Teiid Spring Boot based example as teemplate for any one starting out on new project using the Teiid. 
You can clone the project and start adding your datasources in `Datasources.java` class and corresponding properties 
for connection in `application.properties` and VDB DDL itself if you want create any Views in `/resources/teiid.ddl`

For more information see the [https://github.com/teiid/teiid-spring-boot](https://github.com/teiid/teiid-spring-boot) project, which has many more examples. 
This particular example is done so that the FAT JAR can be captured in a maven repo, which can then be deployed on 
a OpenShift/Kubernetes Cloud cluster.
