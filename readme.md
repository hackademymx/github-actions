# GitHub Actions Introduction

## 1. Presentación del Proyecto

El proyecto con el que se trabajará, es una página web con tres botones, el cual cada uno disparará una petición diferente a un servidor. Dicho proyecto, se compone de dos componentes principales. El primero es el frontend, el cuál será una página construida con React y TypeScript, compilada para hosting estático S3. El segundo componente es un backend hecho con FastAPI y Python, qué sólo constará con un par de rutas.

El código inicial del proyecto se compartirá de manera integra, pues el objetivo del taller no es saber desarrollar estos componentes sino establecer un pipeline a partir de ellos.

## 2. Breve Introducción al CI y CD con GitHub Actions

Explicación superficial acerca de los conceptos de CI y CD, así como sus ventajas y aplicaciones en el mundo profesional del desarrollo de software.
Desarrollo de un pipeline de muestra dentro del ambiente de GitHub Actions para materializar la explicación anterior.

## 3. Construcción de Pipeline Para Backend

Se empezará a construir el pipeline para el backend. Para ellos, tendremos que tener en cuenta los siguientes pasos:

- Testing unitario (hecho con pytest)
- Formateo adecuado del código (hecho con Black)
- Configuración del ambiente de AWS
- Despliegue hacia un ambiente serverless (AWS lambda)

## 4. Construcción del Pipeline Para Frontend

Se construirá un pipeline para el frontend. Para ello, se seguirán los siguientes pasos:

- Testing unitario (hecho con jest)
- Formateo adecuado del código (hecho con Prettier)
- Compilación y construcción de los archivos de distribución (TS)
- Configuración para el ambiente de AWS.
- Despliegue de archivos estáticos a un servidor de hosting (AWS S3 con funcionalidad de Web Server)

## 5. Siguientes Pasos
- Guía acerca de que se puede mejorar en estos flujos (Diferentes ambientes, pruebas A/B, K8s, etc)
- Preguntas finales

## 6. Fechas
El taller se llevará a cabo los días 11 de febrero a las 8:00 PM (Hora CDMX) y 12 de febrero a las 11:00 AM (Hora CDMX)
El taller tiene una cuota de recuperación de 12 dolares.

Registro y pago:
https://buy.stripe.com/dR6cP7dXs9jEfYceV8
