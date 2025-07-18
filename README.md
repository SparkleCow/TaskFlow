# TaskFlow

## Autor:
Jonathan David Ramos Gallego
<br/>

## ¿Qué es TaskFlow?

TaskFlow es una aplicación web que permite a los usuarios registrarse, iniciar sesión y gestionar sus tareas de forma organizada. 
Está diseñada para facilitar el seguimiento de actividades personales o colaborativas, ofreciendo una experiencia sencilla, intuitiva y moderna.

Con TaskFlow puedes:

📝 Crear, editar y eliminar tareas

✅ Marcar tareas como completadas

👥 Registrar usuarios y mantener sesiones seguras

📅 Organizar mejor tu flujo de trabajo diario

Este proyecto es desarrollado como parte de un proceso de aprendizaje en desarrollo web fullstack, combinando tecnologías como Angular (frontend) y Spring Boot (backend), con una arquitectura modular y escalable.

## Tecnologias empleadas (Preliminar)

- Spring y Springboot
- Angular
- JWT y Spring security
- Postman
- Lombok
- Docker
- EC2 (O render)
- TypeScript
- Bootstrap/Tailwind
- MySQL

## Modo de uso (Desarrollo)

- Clona el repositorio: Utiliza el siguiente comando en tu terminal de git - git clone git@github.com:SparkleCow/TaskFlow.git
- Levantar los contenedores: Ejecuta docker-compose up -d para arrancar la base de datos.
- Configurar Spring: Si tienes alguna configuración personalizada o modificas los atributos en docker compose, asegurate de cambiar las variables.
- Configurar Angular: Utiliza npm install para descargar todos los modulos de node empleados para el proyecto.
- Iniciar backend y frontend: Una vez inicializado el contenedor, inicia el servicio de spring y angular (mvn spring-boot:run
  para spring y ng serve para angular)
