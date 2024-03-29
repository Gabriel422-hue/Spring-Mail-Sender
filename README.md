
# Enviando e-mails personalizados com Spring Java Mail Sender e Thymeleaf Template Engine

Nessa aula aprenderemos:
- Enviar e-mails utilizando o Java Mail Sender
- Configurar o Gmail na aplicação
- Enviar um email com uma simples mensagem de texto
- Enviar um email com um template personalizado e dinâmico

## Tecnologias

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa)
- [Lombok](https://projectlombok.org/)
- [H2 Database](https://www.h2database.com/html/quickstart.html)
- [Thymeleaf Template Engine](https://www.thymeleaf.org/documentation.html)

## Configuração do e-mail

````
    spring.mail.default-encoding=UTF-8
    spring.mail.host=smtp.gmail.com
    spring.mail.username=your_email@gmail.com
    spring.mail.password=your_password
    spring.mail.port=587
    spring.mail.protocol=smtp
    spring.mail.test-connection=false
    spring.mail.properties.mail.smtp.auth=true
    spring.mail.properties.mail.smtp.starttls.enable=true
````


## Links úteis

- [Spring Initializr](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.5.5&packaging=jar&jvmVersion=11&groupId=com.example&artifactId=mailsender&name=spring-mail-sender-thymeleaf&description=Demo%20project%20for%20Java%20Mail%20Sender%20and%20Thymeleaf%20template%20engine&packageName=com.example.mailsender&dependencies=web,devtools,data-jpa,h2,lombok,mail,thymeleaf,validation)
- [Spring Mail Doc](https://docs.spring.io/spring-framework/docs/3.2.x/spring-framework-reference/html/mail.html)

## Ambiente e recursos

- Java 11+
- Postman/Insomnia
- HTML e CSS
