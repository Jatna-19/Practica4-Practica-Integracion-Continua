# Práctica 4: Integración Continua con GitHub Actions

## Descripción

En esta práctica se desarrolló un programa básico de Hola Mundo utilizando JavaScript y se configuró un flujo de trabajo con GitHub Actions para automatizar el envío de notificaciones cuando se sube código a la rama `main` del repositorio.

El objetivo es conocer cómo funciona la integración continua y cómo automatizar tareas mediante un archivo de configuración YAML.

## Objetivos

- Crear un programa Hola Mundo en JavaScript.
- Configurar GitHub Actions para ejecutar un flujo de trabajo automático.
- Enviar una notificación utilizando el servicio ntfy.sh.
- Practicar el uso de Git y GitHub para administrar y publicar código.

## Tecnologías utilizadas

- JavaScript
- Git
- GitHub
- GitHub Actions
- ntfy.sh

## Estructura del proyecto

```text
Practica4-Practica-Integracion-Continua/
├── .github/
│   └── workflows/
│       └── alerta.yml
├── index.js
└── README.md
```

## Funcionamiento

El archivo `index.js` contiene el programa que muestra el mensaje Hola Mundo.

El archivo `.github/workflows/alerta.yml` define el flujo de trabajo de GitHub Actions, configurado para ejecutarse cuando se realiza un `push` a la rama `main`.

Durante la ejecución, GitHub Actions ejecuta el programa JavaScript y envía una notificación al tema de ntfy.sh.

## Canal de notificaciones

Tema de ntfy: https://ntfy.sh/devops-itla

## Conclusión

Esta práctica permitió conocer cómo configurar un proceso básico de integración continua utilizando GitHub Actions. También permitió comprender cómo automatizar la ejecución de un programa y el envío de notificaciones al subir cambios a un repositorio, facilitando el seguimiento de las modificaciones realizadas en el proyecto.

## Autora

Jatna De La Cruz

Instituto Tecnológico de las Américas (ITLA)
