# Api_spring



![modelo](https://user-images.githubusercontent.com/67287171/172007958-c1c6adcc-5307-44ac-9cd6-60a4fec6d14e.png)


### H2 Config



````

spring.profiles.active=${APP_PROFILE:test}
spring.jpa.open-in-view=false

---------------


# Dados de conex\uFFFDo com o banco H2
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=

# Configura\uFFFD\uFFFDo do cliente web do banco H2
spring.h2.console.enabled=true
spring.h2.console.path=/h2-console

# Configura\uFFFD\uFFFDo para mostrar o SQL no console
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true

````
