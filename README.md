🚗 Proyecto de Gestión de Automóviles y Estacionamientos

Este proyecto es una aplicación básica de gestión de automóviles y estacionamientos utilizando Java con Spring Boot y JPA (Jakarta Persistence API).

📌 Tecnologías Utilizadas

Java 17+

Spring Boot

Spring Data JPA

Hibernate

Base de datos relacional (MySQL, PostgreSQL u otra compatible con JPA)

Jakarta Persistence API (JPA)

📌 Clases Principales

1. Automovil

Representa un automóvil con una relación @ManyToOne hacia Estacionamiento.

2. Estacionamiento

Representa un estacionamiento con una relación @OneToMany hacia Automovil.

