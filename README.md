# KIT-INPIA

Kurz programování internetových aplikací určen pro začínající programátory, kteří již mají zkušenosti v oblasti tvorby webů. Prerekvizitou je znalost principů OOP.

Pro zopakování základních znalostí využijte materiály [KIT-IWWW](https://github.com/petrfilip/KIT-IWWW), které v tomto kurzu využijete. Jedná se především o
[HTML](https://github.com/petrfilip/KIT-IWWW/tree/1-www-html-css),
[CSS](https://github.com/petrfilip/KIT-IWWW/tree/2-www-html-css-responsive),
[SQL](https://youtu.be/1d85TID3V4U),
[JavaScriptu](https://github.com/petrfilip/KIT-IWWW/tree/7-javascript-basics) a
[AJAX](https://github.com/petrfilip/KIT-IWWW/tree/8-ajax)

Dále doporučuji video o [Gitu a Githubu od základů](https://www.youtube.com/watch?v=0v5K4GvK4Gs).

Pro vývoj bude vaše oblíbené IDE
(například [IntelliJ Idea](https://www.jetbrains.com/idea/), [toolbox](https://www.jetbrains.com/toolbox-app/) pro snadné aktualizace),
[NodeJS](https://nodejs.org/en/) a
[NPM](https://www.npmjs.com/.

V kurzu se podíváme na následující témata:

1. Úvod do Spring Bootu
    - porovnání PHP a Javy
    - 1..N důvodů proč Spring Boot
    - Spring starter a dostupné moduly
    - vytvoření první aplikace (základní patterny, debugování java aplikace, @Autowired, @Service,)
    - Spring MVC
    - Thymeleaf
    - vytvoření JUnit testu
2. Vytvoření eshopu ve Spring Bootu
    - model first, code first, flyway
    - ORM - @OneToMany, @Column, @Transactional, extends JpaRepository, findBy... s JPA plus jen s JdbcTemplate,
    - @Endpoint, @RestController
    - Rest klienti (Insomnia, Postman, http, CURL)
    - vytvoření testu s @DataJpaTest
    - @Cacheable
3. Rest API & JavaScript klient
    - zopakování HTTP protokolu
    - vytvoření JavaScript klienta
    - spring security (RBAC)
    - zabezpečení pomocí (JWT + hackování)
    - JWT
    - debugování JavaScriptu
    - testování endpointů
4. Úvod do Reactu
    - NodeJS, NPM, package.json
    - první aplikace v Reactu
    - komponenty
    - state vs props
    - hooky (state, efect)
    - context
5. React + Spring - napojení react aplikace na backend
    - deklarativní klient pro načítání dat
    - komponenty pro výpis dat
    - detail položky

N. Bonus - Spring Cloud - implementace microservice architektury ([e-commerce ukázka](https://github.com/petrfilip/simpleshop-spring-cloud-example))

![Spring Cloud](https://github.com/petrfilip/simpleshop-spring-cloud-example/blob/master/images/architecture.png)

## Doporučené zdroje

- [baeldung](https://www.baeldung.com/spring-boot-start) - spousta návodů na vše, co se týká springu a spring bootu
- [React JS](https://reactjs.org/docs/getting-started.html) - oficiální tutoriál pro React

TODO

- [ ] Implementace message brokera
- [ ] Využití Apache Camel
- [ ] Integrace s Apache Kafka