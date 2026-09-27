# Hi, I'm Hatim 👋

Backend developer specialized in Java and Spring Boot, with a solid foundation in full stack web development. I like building backends where the architecture actually makes sense and the code doesn't turn into a mess six months later. I apply Clean Code and SOLID not because the job posting asks for it, but because I consider it part of doing the job right.

Currently looking for my first stable position as a Java developer. **Available for immediate start.**

---

> La versión en español se encuentra abajo ↓↓↓

---

## 🛠️ Stack

**Backend** - `Java 21` `Spring Boot` `REST APIs` `Apache Kafka` `Spring Security` `WebSocket/STOMP` `PHP`

**Frontend** - `JavaScript ES6+` `React` `Bootstrap` `Thymeleaf` `HTML5` `CSS3`

**Persistence** - `JPA/Hibernate` `MySQL` `PostgreSQL`

**Testing & Quality** - `JUnit 5` `Mockito` `Clean Code` `SOLID` `Bean Validation`

**DevOps** - `Docker` `Github Actions` `Git` `Maven` `Nginx`

---

## 🚀 Projects

### 📦 [Real-Time Order & Inventory System - Microservices](https://github.com/DebHatim/pedidos-microservicios)
`Java 21` `Spring Boot 4.1` `Spring Cloud Gateway` `Apache Kafka` `Resilience4j` `Redis` `Prometheus` `Grafana` `Jaeger` `Docker` `React`

E-commerce platform built on 4 independent microservices (gateway, orders, inventory, notifications) communicating asynchronously via Kafka, with full resilience and observability.

- Event-driven architecture with a database per service and eventual consistency via Kafka (KRaft)
- Centralized gateway with rate limiting (Redis), retries and per-service circuit breaker with fallback controllers
- Full observability of the distributed system: metrics (Prometheus/Grafana) and distributed tracing (OpenTelemetry/Jaeger)
- Integration tests with Testcontainers (real MySQL + Kafka) verifying the full end-to-end flow

### 🔔 [Real-Time Price Alerts System](https://github.com/DebHatim/alertas-tiempo-real)
`Java 21` `Spring Boot 3.5` `Apache Kafka` `React` `WebSocket` `Spring Security` `JWT` `MySQL` `Docker`

Event-driven platform where users set price alerts and get instant push notifications via Kafka + WebSocket the moment a target price is hit, no polling.

- Kafka producer/consumer decoupling: price simulator publishes events, consumer evaluates active alerts and triggers real-time notifications
- Instant WebSocket/STOMP notifications with resource-level authorization (IDOR prevention)
- Stateless JWT auth with Spring Security and BCrypt; rate limiting on login with Bucket4j
- Full test suite (JUnit 5 + Mockito) with CI/CD via GitHub Actions; single-command deploy with Docker Compose

### 🏨 [Hotel Reservation Management System](https://github.com/DebHatim/reservasSpringBoot)
`Java 21` `Spring Boot 4` `Spring Security` `JPA/Hibernate` `MySQL` `Thymeleaf`

REST API and backend web application for full hotel and reservation management, with role-based auth and double-booking prevention.

- Role-based authentication and authorization (ROLE_USER / ROLE_ADMIN) with Spring Security 6 + BCrypt
- Double-booking prevention algorithm in the service layer with JPQL validation
- Admin panel with full CRUD for hotels and users
- Dynamic views with Thymeleaf and REST API via Spring Data REST

---

## ⚡ Fun Facts

🎵 My coding sessions have the feel of **R&B** music. I believe software and music have a lot in common: if one piece is out of place in the architecture, you have to fine-tune it until the whole system sounds perfect.

🐛 I suffer from "stubborn bug syndrome": if a technical problem beats me during the day, my brain will likely solve it while I'm having dinner or trying to sleep.

---

## 📫 Contact

[![Portfolio](https://img.shields.io/badge/Portfolio-hatimdebboun.dev-emerald)](https://hatimdebboun.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hatimdebboun-blue?logo=linkedin)](https://linkedin.com/in/hatimdebboun)
[![Email](https://img.shields.io/badge/Email-thos.debboun.hatim@gmail.com-red?logo=gmail)](mailto:thos.debboun.hatim@gmail.com)

---

<details>
<summary>🇪🇸 Versión en español</summary>
<br>
  
# Hola, soy Hatim 👋

Desarrollador backend especializado en Java y Spring Boot, con base sólida en desarrollo web full stack. Me gusta construir backends bien estructurados donde la arquitectura tiene sentido y el código se pueda mantener sin que sea un caos en seis meses. Aplico Clean Code y SOLID no porque los pida la oferta, sino porque lo considero parte de hacer bien el trabajo.

Actualmente buscando mi primer empleo estable como desarrollador Java. **Disponible para incorporación inmediata.**

---

## 🛠️ Stack

**Backend** - `Java 21` `Spring Boot` `REST APIs` `Apache Kafka` `Spring Security` `WebSocket/STOMP` `PHP`

**Frontend** - `JavaScript ES6+` `React` `Bootstrap` `Thymeleaf` `HTML5` `CSS3`

**Persistencia** - `JPA/Hibernate` `MySQL` `PostgreSQL`

**Testing y calidad** - `JUnit 5` `Mockito` `Clean Code` `SOLID` `Bean Validation`

**Herramientas** - `Docker` `Github Actions` `Git` `Maven` `Nginx`

---

## 🚀 Proyectos

### 📦 [Sistema de Pedidos e Inventario - Microservicios](https://github.com/DebHatim/pedidos-microservicios)
`Java 21` `Spring Boot 4.1` `Spring Cloud Gateway` `Apache Kafka` `Resilience4j` `Redis` `Prometheus` `Grafana` `Jaeger` `Docker` `React`

Plataforma de e-commerce basada en 4 microservicios independientes (gateway, pedidos, inventario, notificaciones) comunicados de forma asíncrona vía Kafka, con resiliencia y observabilidad completas.

- Arquitectura orientada a eventos con base de datos propia por servicio y consistencia eventual vía Kafka (KRaft)
- Gateway centralizado con rate limiting (Redis), reintentos y circuit breaker por servicio, con fallback controllers
- Observabilidad completa del sistema distribuido: métricas (Prometheus/Grafana) y tracing distribuido (OpenTelemetry/Jaeger)
- Tests de integración con Testcontainers (MySQL + Kafka reales) verificando el flujo completo extremo a extremo

### 🔔 [Sistema de Alertas de Precios en Tiempo Real](https://github.com/DebHatim/alertas-tiempo-real)
`Java 21` `Spring Boot 3.5` `Apache Kafka` `React` `WebSocket` `Spring Security` `JWT` `MySQL` `Docker`

Plataforma basada en eventos donde los usuarios configuran alertas de precios y reciben notificaciones push instantáneas a través de Kafka + WebSocket en el momento en que se alcanza un precio objetivo, sin necesidad de sondeo.

- Desacoplamiento productor/consumidor de Kafka: el simulador de precios publica eventos, el consumidor evalúa las alertas activas y activa notificaciones en tiempo real.
- Notificaciones instantáneas WebSocket/STOMP con autorización a nivel de recurso (prevención IDOR)
- Autenticación JWT stateless con Spring Security y BCrypt; rate limiting en el inicio de sesión con Bucket4j.
- Suite de tests completa (JUnit 5 + Mockito) con CI/CD a través de GitHub Actions; despliegue con un solo comando mediante Docker Compose

### 🏨 [Sistema de Gestión de Reservas Hoteleras](https://github.com/DebHatim/reservasSpringBoot)
`Java 21` `Spring Boot 4` `Spring Security` `JPA/Hibernate` `MySQL` `Thymeleaf`

API REST y aplicación web de backend para la gestión integral de hoteles y reservas, con autenticación basada en roles y prevención de reservas duplicadas.

- Autenticación y autorización basadas en roles (ROLE_USER / ROLE_ADMIN) con Spring Security 6 + BCrypt
- Algoritmo de prevención de reservas duplicadas en la capa de servicio con validación JPQL
- Panel de administración con CRUD completo y DTO para desacoplamiento de capas.
- Arquitectura MVC por capas con Bean Validation para la integridad de los datos.

---

## ⚡ En lo personal

🎵 Mis sesiones de código suenan a ritmo de **música R&B**. Creo que el software y la música tienen mucho en común: si una pieza desentona en la arquitectura, toca afinarla hasta que todo el sistema suene perfecto.

🐛 Sufro del "síndrome del bug persistente": si un problema técnico se me resiste durante el día, mi cerebro probablemente lo acabará resolviendo mientras ceno o intento dormir.

---

### 📫 Contacto

[![Portfolio](https://img.shields.io/badge/Portfolio-hatimdebboun.dev-emerald)](https://hatimdebboun.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hatimdebboun-blue?logo=linkedin)](https://linkedin.com/in/hatimdebboun)
[![Email](https://img.shields.io/badge/Email-thos.debboun.hatim@gmail.com-red?logo=gmail)](mailto:thos.debboun.hatim@gmail.com)

</details>
