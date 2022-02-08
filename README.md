# Hibernate-Security
### Цель задания
____

**Задание 1.** Создать Spring boot приложение, которое будет работать с БД через чистый Hibernate и через JPARepository с запросами от имени методов и запросами от аннотации  @Query

**Задание 2.** Подключить к приложению Spring Security, реализовать аутентификацию пользователя по логину и паролю, реализовать авторизацию и разграничение доступов к методам контроллера в зависимости от ролевой модели

___

### Реализация

**Задание 1.** Чистый хибер реализован в ветке */master*. Получение в запросах от имени метода в ветке */jpa-repository*, получение в запросах с аннотацией @Query в ветке */jpa-repository-query*

**Задание 2.** Аутентификацию подключил в ветке */security*, авторизацию и защиту методов в ветке */role-model*
