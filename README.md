# Componente API Gateway - Filler

## Descripción
Este componente actúa como el punto único de entrada para todas las peticiones levantadas desde el frontend de React, se encarga de centralizar el tráfico de red, abstrayendo la arquitectura interna y aplicando el enrutamiento hacia los microservicios traseros (`back-main` y `resumen`)

## Tecnologías Utilizadas
* Java con Spring Boot

## Requisitos e Instalación
* Clonar el repositorio
* Validar el mapeo de rutas configurado hacia los puertos correspondientes en el archivo de propiedades de Spring
* Ejecutar con el [botón de Ejecutar](https://i.imgur.com/pWEN7D2.png) o con el comando para ejecutar de manera local: `.\mvnw.cmd spring-boot:run`
