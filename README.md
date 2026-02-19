<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Nest-Car-Dealership

API básico para gestión de coches creado con [Nest](https://github.com/nestjs/nest).

## Configuración del proyecto

```bash
$ npm install
```

## Compilar y ejecutar el proyecto

```bash
# desarrollo
$ npm run start

# modo observación
$ npm run start:dev

# modo producción
$ npm run start:prod
```

## Ejecutar pruebas

```bash
# pruebas unitarias
$ npm run test

# pruebas e2e
$ npm run test:e2e

# pruebas de cobertura
$ npm run test:cov
```

## Aspectos analizados

En este proyecto se genera una API Rest básica con Nest y se analizan los siguientes puntos:
- Estructura básica de un proyecto Nest
- Building blocks: 
  - módulos
  - controladores
  - decoradores básicos
  - servicios
  - inyección de dependencias
  - pipes
  - exception filters
- DTO
- Validaciones automáticas con class validator y class transformer
- Seed endpoint
- Módulos enlazados
- Entidades

## Librerías necesarias

La generación de identificadores se efectúa con [UUID](https://www.npmjs.com/package/uuid):
```bash
$ npm install uuid
```

Las clases Validator y Transformer necesarias para el ValidationPipe se instalan con:
```bash
$ npm i class-validator class-transformer
```