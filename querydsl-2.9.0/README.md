# querydsl-2.9.0 ServiceMix Bundle
This bundle packages the following querydsl artifacts:
+ querydsl-core
+ querydsl-apt
+ querydsl-codegen
+ querydsl-jdo
+ querydsl-lucene
+ querydsl-sql

## Bundle Execution
To run the bundle, it is required to install the following prerequistes:
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

Installing the bundle can be achieved by executing the following command:
```
osgi:install mvn:org.apache.servicemix.bundles/org.apache.servicemix.bundles.querydsl/2.9.0_1-SNAPSHOT
```
