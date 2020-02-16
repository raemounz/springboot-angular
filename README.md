# Spring Boot and Angular

This is a seed project using Spring Boot for backend and Angular for frontend.

The frontend provides named build configurations for development, staging,
and production environments respectively:

- environment.ts
- environment.staging.ts
- environment.prod.ts

The project uses the following:

- Angular Material for material design components
- Angular Flex-Layout for responsive UI layout

## Preview
![Spring Boot and Angular Preview](ui/src/assets/preview.png)

## Build

To build the project for staging, run `mvn clean install -Pnpm-build-staging`.

To build the project for production, run `mvn clean install -Pnpm-build`.

The build artifacts will be stored in the `target/` directory.

## Run

Run the following in the command prompt:

`java -jar target/springbootangular-0.0.1-SNAPSHOT.jar`

Navigate to http://localhost:8080/.