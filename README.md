# melchor-services-manifiestos
Sistema de gestión de manifiestos -Melchor Services S.A.C.(Tema 6, CIIN1322P)
Curso: Modelado y Desarrollo de Aplicaciones (CIIN1322P) – UPN
Tema 6: Planificación iterativa con RUP + coherencia de artefactos UML por fase

## Equipo
- Marvin Yahir Melchor Cruz
- Josué Leyva Aguilar
- Jaime Patrizio Rafael Fernandini Cano
- Cristian David López Cruz
- Piero Alexis Ojeda Herrera

## Estructura
| Carpeta | Contenido |
|---|---|
| docs/gestion | Roadmap, registro de riesgos, actas |
| docs/I1-inicio | Visión v1.0, contexto, mapa de procesos |
| docs/E1-requisitos | SRS breve, checklist, matriz de conflictos |
| docs/E2-casos-de-uso | CUN, CUS, especificaciones CU-04, CU-05, CU-08 |
| docs/E3-modelado | Prototipos W1-W8, diagramas UML, paquetes |
| docs/E4-backlog | Historias de usuario, Gherkin, DoD |
| docs/trazabilidad | Matriz de trazabilidad, checklist, hallazgos |
| modelos | Archivos fuente de Modelio |
| evidencias | Exportaciones PNG/PDF por iteración |
| src | Código (C1 a C4) |

## Convenciones
- **Ramas:** `main` solo contiene versiones publicadas; el trabajo va en `feature/<iteración>-<tema>` (ej. `feature/I1-vision`).
- **Commits:** `tipo(alcance): descripción`, citando IDs. Tipos: docs, model, feat, fix, chore.
- **Tags:** `v<mayor>.<menor>-iter<n>` (ej. `v1.0-iter1`).
- **IDs:** RF-nn, CU-nn, EX-nn, R-nn, EV-nn.
- **Integración:** todo cambio entra a `main` por pull request con un revisor.