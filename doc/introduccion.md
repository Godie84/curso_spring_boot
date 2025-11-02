### Spring.io
Inicialzr

Dependencias más utilizadas

1. spring-boot-starter-web

👉 Para crear APIs REST o aplicaciones web.

Incluye:

Spring MVC

Jackson (para JSON)

Tomcat (servidor embebido)

💡 Ejemplo de uso: controladores @RestController, endpoints @GetMapping, etc.

2. spring-boot-starter-data-jpa

👉 Para trabajar con bases de datos relacionales usando JPA e Hibernate.

Incluye:

Spring Data JPA

Hibernate ORM

Soporte para bases como MySQL, PostgreSQL, H2, etc.

💡 Permite usar interfaces tipo JpaRepository para acceder a la base de datos sin escribir SQL manualmente.

3. spring-boot-starter-security

👉 Añade autenticación y autorización a tu aplicación.

Incluye:

Spring Security (manejo de roles, sesiones, contraseñas)

Integración con JWT, OAuth2, etc.

💡 Protege endpoints, controla accesos, maneja usuarios y contraseñas.

4. spring-boot-starter-validation

👉 Para validar datos de entrada, por ejemplo en peticiones REST.

Incluye:

Hibernate Validator

Anotaciones como @NotNull, @Email, @Size, etc.

💡 Ejemplo:

public class Usuario {
@NotNull
private String nombre;

    @Email
    private String correo;
}

5. spring-boot-starter-test

👉 Incluye librerías para tests unitarios e integrales.

Incluye:

JUnit 5

Mockito

Spring Test

💡 Permite probar controladores, servicios, repositorios, etc.

6. spring-boot-starter-thymeleaf

👉 Si tu aplicación tiene vistas web (HTML dinámico).

Incluye:

Thymeleaf (motor de plantillas)

Integración con Spring MVC

💡 Ideal para aplicaciones con frontend server-side (por ejemplo, paneles de administración).

7. spring-boot-starter-actuator

👉 Añade endpoints de monitorización y métricas.

Incluye:

/actuator/health (estado)

/actuator/metrics (rendimiento)

/actuator/info (información de la app)

💡 Muy útil en producción y con herramientas de observabilidad como Prometheus o Grafana.

8. springdoc-openapi-ui (Swagger)

👉 No es parte del core de Spring Boot, pero muy popular para documentar APIs.

<dependency>
    <groupId>org.springdoc</groupId>
    <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
    <version>2.6.0</version>
</dependency>


💡 Te da acceso a una interfaz en /swagger-ui.html donde puedes probar tus endpoints REST.

9. spring-boot-starter-mail

👉 Para enviar correos electrónicos desde tu aplicación.

Incluye:

Spring Mail

JavaMailSender

💡 Ejemplo: enviar notificaciones o confirmaciones de registro.

10. spring-boot-devtools

👉 Herramienta de desarrollo rápido: recarga automática del proyecto al guardar cambios.

💡 Acelera el ciclo de desarrollo sin reiniciar manualmente el servidor.

🧠 Tip

Puedes ver todas las dependencias disponibles en el sitio oficial:
👉 https://start.spring.io

Ahí seleccionas lo que necesites, y Spring Boot genera el proyecto completo con las dependencias listas.