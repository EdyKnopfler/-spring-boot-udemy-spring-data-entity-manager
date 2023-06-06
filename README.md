# spring-boot-udemy-spring-data-entity-manager

Aquecendo meu Spring Boot pelo [curso da Udemy](https://www.udemy.com/course/spring-boot-expert/).

Esta aula cria um repositório "na mão" usando `EntityManager`. Tive um problema para injetar o objeto e não conseguia porque estava
declarando a classe do pacote `javax.persistence` e deveria ser `jakarta.persistence`. Da mesma forma, as anotações de entidade devem
vir desse pacote (ver a classe `Cliente`).

Somente um repositório com controlador foi criado, o de Clientes, para demonstrar esse uso. O objetivo é ter documentado para o caso
de esbarrar com o `EntityManager` por aí. O projeto continua no repositório https://github.com/EdyKnopfler/spring-boot-udemy-spring-data,
quer irá usar os _JPA Repositories_ do Spring Boot.
