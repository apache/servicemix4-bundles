# spring-data-neo4j-2.2.2.RELEASE ServiceMix Bundle
This bundle packages the following spring-data-neo4j artifacts:
* spring-data-neo4j
* spring-data-neo4j-aspects
* spring-data-neo4j-cross-store
* spring-data-neo4j-tx
* spring-data-neo4j-rest

## Bundle Execution
To run the bundle, it is required to install the following prerequisites:

1. querydsl-2.9.0 requirements
```
osgi:install mvn:org.apache.geronimo.specs/geronimo-jta_1.1_spec/1.1.1
osgi:install mvn:org.apache.servicemix.specs/org.apache.servicemix.specs.java-persistence-api-1.1.1/2.4.0
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.guava/11.0.2_2
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.javax-inject/1_2
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.jdo2-api/2.2_1
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.cglib/2.2.2_1
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.lucene/3.0.3_2
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.jdt-core/3.2.3_5
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.joda-time/2.3_1
```

2. querydsl-2.9.0
```
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.querydsl/2.9.0_1-SNAPSHOT
```

3. spring-data-neo4j-2.2.2.RELEASE requirements
```
osgi:install mvn:org.apache.servicemix.specs/org.apache.servicemix.specs.jsr303-api-1.1.0/2.4.0
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.neo4j/1.8_2
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.aopalliance/1.0_6
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.aspectj/1.7.2_1
osgi:install mvn:org.springframework/spring-core/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-asm/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-expression/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-beans/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-aop/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-context/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-context-support/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-tx/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-jdbc/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-orm/3.1.4.RELEASE
osgi:install mvn:org.apache.servicemix.specs/org.apache.servicemix.specs.activation-api-1.1/2.2.0
osgi:install mvn:org.apache.geronimo.specs/geronimo-servlet_2.5_spec/1.2
osgi:install mvn:javax.mail/mail/1.4.5
osgi:install mvn:org.apache.geronimo.specs/geronimo-jta_1.1_spec/1.1.1
osgi:install mvn:org.eclipse.jetty/jetty-util/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-io/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-http/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-client/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-continuation/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-jmx/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-server/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-security/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-servlet/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-servlets/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-xml/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-webapp/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-jndi/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-plus/7.6.8.v20121106
osgi:install mvn:org.eclipse.jetty/jetty-websocket/7.6.8.v20121106
osgi:install mvn:org.ops4j.pax.web/pax-web-api/1.1.14
osgi:install mvn:org.ops4j.pax.web/pax-web-spi/1.1.14
osgi:install mvn:org.ops4j.pax.web/pax-web-runtime/1.1.14
osgi:install mvn:org.ops4j.pax.web/pax-web-jetty/1.1.14
osgi:install mvn:org.springframework/spring-web/3.1.4.RELEASE
osgi:install mvn:org.springframework/spring-webmvc/3.1.4.RELEASE
```

4. Installing the bundle can be achieved by executing the following command:
```
// spring-data-neo4j-2.2.2.RELEASE
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.spring-data-neo4j/2.2.2.RELEASE_1-SNAPSHOT
```

