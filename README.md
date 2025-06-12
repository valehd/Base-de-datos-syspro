Proyecto Base de Datos Relacional (MySQL)

1. Estructura general:
- El sistema incluye usuarios (técnicos y administradores), proyectos, etapas, asignaciones, registros de horas, comentarios y bitácora de acciones.
- Las relaciones están normalizadas y cada entidad tiene su clave primaria y relaciones foráneas correspondientes.

2. Relaciones clave:
- Un proyecto tiene muchas etapas.
- Una etapa puede tener varios técnicos (N:M a través de la tabla Asignacion).
- RegistroHoras enlaza usuarios y etapas con marca temporal.
- Comentario y Bitacora permiten trazabilidad de acciones.

3. Cómo ejecutar:
- Crear la base de datos ejecutando `creacion_syspro.sql`.
- Poblar las tablas con `datos_syspro.sql`.
- Revisar el modelo visual en `modelo_syspro.pdf` (no incluido aquí).

Autor: Valentina Hernández Díaz
Carrera: Analista Programador
Año: 2025
