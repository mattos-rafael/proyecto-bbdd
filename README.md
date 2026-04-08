# Proyecto BBDD

## Descripción del proyecto
Este proyecto tiene como objetivo transformar una tabla plana con datos de alumnado y claustro en una base de datos relacional normalizada.

A partir de varios archivos CSV, se trabaja la limpieza, organización y estructuración de los datos para construir un modelo relacional en PostgreSQL, acompañado de su diagrama E/R, modelo lógico, scripts SQL y consultas de prueba.

---

## Objetivo
Diseñar una base de datos funcional y escalable que permita:

- separar entidades correctamente
- reducir redundancia
- mantener integridad referencial
- consultar la información de forma clara y eficiente

---

## Flujo general del proyecto

```text
CSV data
↓
Python + pandas
↓
PostgreSQL
↑
pgAdmin 4
