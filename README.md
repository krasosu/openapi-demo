# OpenAPI Demo Project


# 
Then when we run our application, the OpenAPI descriptions will be available at the path /v3/api-docs by default:

`http://localhost:8080/v3/api-docs/`

To use a custom path, we can indicate in the application.properties file:

`springdoc.api-docs.path=/api-docs`

The OpenAPI definitions are in JSON format by default. For yaml format, we can obtain the definitions at:

`http://localhost:8080/api-docs.yaml`


### Swagger-UI

The springdoc-openapi dependency already includes Swagger UI, so we're all set here.

`http://localhost:8080/swagger-ui.html`

For example, let's customize the path of our API documentation. We can do this by modifying our application.properties to include:

`springdoc.swagger-ui.path=/swagger-ui-custom.html`
