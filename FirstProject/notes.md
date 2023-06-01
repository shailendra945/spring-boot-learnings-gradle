1.this project is only starting project which cover how create spring boot project.
2.@SpringBootApplication annotation is composite annotation or meta annotation which basically wrap three others annotation
  @SpringBootConfiguration - tells to spring boot its a configuration class
  @EnableAutoConfiguration -  use for enabling autoconfiguration
  @ComponentScan    - used for scanning the current package and its subpackages for configuration and spring component i.e beans , services , repository etc.

3.SpringApplication.run(Class class,String  args) method is entry point for spring boot application , which read through the class , scan the annotations and create application context and return it.
4.org.springframework.boot:spring-boot-starter is  minimum dependency to start with spring boot application.if we including the web dependency this will this will automatically added by spring boot.
5.we can run our application using [<your project root>:\ gradle clean bootRun ], task.
6.Since we have not added any web dependency yet it run and show you some output and stopped.