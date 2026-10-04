# SIAA

Sistema Integral Actuarial ActuNova.

## Alcance del proyecto

- Migrar la calculadora PNU de Excel a un motor de calculos con ajuste de edad y resultados para seguros temporal, dotal y dotal mixto.
- Utilizar las tablas CNSF 2013 acordadas como datos de referencia fijos, con identificacion de la tabla aplicada a cada calculo.
- Registrar cada corrida, sus entradas, resultados y autor en una base de datos central compartida por el equipo.
- Permitir la captura de nuevos calculos y la consulta del historial desde la interfaz mediante un backend.
- Generar reportes Excel y proporcionar datos para el dashboard de Power BI.
- Validar los resultados del motor contra la calculadora Excel de referencia.

## Ramas

| Rama | Trabajo previsto |
| --- | --- |
| main | Version estable |
| develop | Integracion del desarrollo |
| docs/especificacion-actuarial | Reglas, alcance y especificaciones |
| data/cnsf-2013-tablas | Tablas de referencia CNSF 2013 |
| feature/motor-actuarial-pnu | Motor de calculos PNU |
| feature/base-datos-servidor | Persistencia central compartida |
| feature/api-backend | API y backend |
| feature/interfaz-captura-resultados | Captura, resultados e historial |
| reports/excel | Reportes Excel |
| reports/powerbi | Integracion de datos con Power BI |
| tests/validacion-excel | Validacion contra Excel |

## Estado

Este commit inicial documenta el alcance y permite crear las ramas remotas. El codigo preparado en el proyecto local todavia no se ha incorporado a este repositorio.
