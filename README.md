                                                    configuration_server_service
1)About the project.

This is a Spring Cloud Сonfig microservice, it is a central service for configuration for all other services in the system.

2)Start the project locally.

2.1 Required to install the project.

Java 11

2.2 How to run project.

You should create environmental variables that are defined in the resources package like:

application.properties.

2.2.1 For application.properties you should set the value like:

* spring.application.name=${Value}
* server.port=${Value}
* spring.cloud.config.server.git.uri=${Value}
* spring.cloud.config.server.git.username=${Value}
* spring.cloud.config.server.git.password=${Value}
* spring.cloud.config.server.git.clone-on-start=${Value}
