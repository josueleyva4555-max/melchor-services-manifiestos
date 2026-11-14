## Matriz de riesgos del proyecto

| ID | Fase | Riesgo | Prob. | Impacto | Mitigación |
|---|---|---|---|---|---|
| R-01 | Inicio | Alcance difuso: funciones excluidas (facturación, contabilidad, GPS) vuelven a solicitarse, o funciones como RF-13 y RF-14 no están validadas. | Media | Alto | Validar el alcance con el gerente en una reunión, fijar el Documento de Visión v1.0 y aplicar control de cambios (criterio de la sección 5.2). |
| R-02 | Inicio | Poca disponibilidad de la secretaria o del gerente para validar requisitos. | Media | Alto | Programar las reuniones de validación desde I1 y dejar actas firmadas. |
| R-03 | Elaboración | Intereses distintos entre gerente, secretaria, contadora y empresas clientes. | Media | Medio | Documentar y resolver conflictos en la matriz de stakeholders de E1. |
| R-04 | Elaboración | Sobrecarga de E3: prototipos y cuatro tipos de diagrama a cargo de un solo integrante en 2 semanas. | Alta | Medio | Repartir los diagramas entre dos integrantes y priorizar los del módulo crítico (sección 4). |
| R-05 | Construcción | Resistencia al cambio de la secretaria y los conductores, acostumbrados al manifiesto en papel. | Media | Alto | Involucrarlos en la revisión de los prototipos W1-W8 y hacer una demostración al cierre de C2. |
| R-06 | Construcción | Los conductores no tienen conexión estable en ruta; la suposición de internet cubre solo la oficina. | Alta | Alto | Estado "Pendiente de envío" (EX-05), requisito no funcional de operación sin conexión y prueba específica en C2. |
| R-07 | Construcción | Exposición de datos personales de pasajeros y conductores (Ley N.° 29733). | Media | Alto | Roles y permisos (RF-11), acceso restringido para la contadora y requisito de seguridad definido en E1. |
| R-08 | Transición | Datos inconsistentes o incompletos en los Excel históricos al migrarlos. | Alta | Medio | Revisar una muestra de los Excel en E1, conservar una copia de respaldo y validar la migración con la secretaria en T1. |
| R-09 | Transición | Pérdida de manifiestos mientras conviven el papel y el sistema. | Media | Alto | Periodo de uso paralelo corto y registro de los manifiestos físicos pendientes durante T1. |
| R-10 | Todas | Los artefactos se desalinean cuando cambian los requisitos. | Media | Medio | Actualizar la matriz de trazabilidad en cada iteración y hacer revisión por pares (sección 8). |