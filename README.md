# Read Me First
This project uses `SpringBoot` and OpenAPI Maven `openapi-generator-maven-plugin` plugin to generate Java classes for Flagsmith OpenAPI specification

# Getting Started
Inside pom.xml file, under openapi-generator-maven-plugin attributes, set the desired packages for API and model of the generated code.
After cloning, run Maven clean + install.
During Maven test phase, *FlagsmithOpenapiApplicationTests* will run , and load SpringBoot context. you can use these tests.
One might also startup a SpringBoot Application using the already given *FlagsmithOpenapiApplication* class.
The generated code will reside under /target/classes directory.

### Reference Documentation


* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [OpenAPI Maven Plugin](https://github.com/OpenAPITools/openapi-generator/tree/master/modules/openapi-generator-maven-plugin)
* [Flagsmith API documentation](https://docs.flagsmith.com/clients/rest/#api-explorer)
* [Flagsmith Swagger](https://api.flagsmith.com/api/v1/docs/)
* [Flagsmith OpenAPI schema](https://api.flagsmith.com/api/v1/docs/?format=openapi)

