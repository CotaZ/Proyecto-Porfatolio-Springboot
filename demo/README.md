# Proyecto Portafolio ejemplo Spring Boot 

Este proyecto es una aplicación web desarrollada con **Spring Boot**. Además, utiliza **Thymeleaf** para renderizar vistas HTML y Bootstrap para el diseño de la interfaz de usuario.

## Características

- **Framework Backend**: Spring Boot.
- **Motor de Plantillas**: Thymeleaf para renderizar vistas dinámicas.
- **Frontend**: HTML5, CSS3, Bootstrap 5.
- **Puerto Configurado**: La aplicación se ejecuta en el puerto `8081`.

## Estructura del Proyecto

Proyecto SpringBoot/

├── pom.xml                      # Configuración de dependencias de Maven

├── README.md                    # Documentación principal del proyecto

├── src/

│   ├── main/

│   │   ├── java/

│   │   │   └── com/

│   │   │       └── example/
│   │   │           └── demo/    # Paquete principal de la aplicación
│   │   │               ├── config/       # Configuraciones de configuración de la aplicación
│   │   │               ├── controller/   # Controladores REST
│   │   │               ├── model/        # Entidades y DTOs
│   │   │               ├── repository/   # Interfaces de repositorio (JPA)
│   │   │               ├── service/      # Lógica de negocio
│   │   │               ├── util/         # Utilidades y helpers
│   │   │               └── DemoApplication.java  # Clase main
│   │   └── resources/
│   │       ├── static/          # Recursos estáticos
│   │       │   ├── css/         # Hojas de estilo
│   │       │   ├── js/          # JavaScript
│   │       │   └── images/      # Imágenes
│   │       ├── templates/       # Vistas Thymeleaf
│   │       ├── application.properties  # Config principal
│   │       └── application-{profile}.properties  # Configs por entorno
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── demo/    # Pruebas unitarias e integración
│                       ├── controller/
│                       ├── service/
│                       └── integration/  # Pruebas de integración con APIGEE
└── target/                   # Artefactos generados (ignorar en control de versiones)


## Requisitos Previos

- **Java 17** o superior.
- **Maven** para la gestión de dependencias.
- Un navegador web para probar la interfaz.

## Configuración

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/proyecto-springboot.git
   cd proyecto-springboot-apigee

2. Configura la base de datos en el archivo application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/nombre_base_datos
spring.datasource.username=usuario
spring.datasource.password=contraseña

3. Instala las dependencias:

- mvn clean install

4. Ejecuta la aplicación:

- mvn spring-boot:run

5. Ejecuta la aplicación:

- Abre tu navegador y accede a http://localhost:8081.

Tecnologías Utilizadas
- Spring Boot: Framework para el desarrollo backend.
- Thymeleaf: Motor de plantillas para renderizar vistas HTML.
- Bootstrap: Framework CSS para diseño responsivo.
- APIGEE: Gestión de APIs.

## Autor
Luis Álvarez
Analista Programador - Desarrollador Full Stack

¡Siéntete libre de contribuir al proyecto o reportar problemas en el repositorio!

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

