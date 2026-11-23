# CLAUDE.md

Guía para Claude Code y otros asistentes que trabajen en este repositorio.

## Qué es este repositorio

Repositorio de trabajo de **Precisión**, consultora de crecimiento comercial B2B
(Chile). Guarda documentos de trabajo de la consultora, no una aplicación: no hay
código, dependencias, compilación ni pruebas.

Todo texto se escribe en español de Chile y sigue el **canon de Precisión**
(registro, cifras en formato es-CL, usted al cliente, sin nombres de personas en
entregables). El canon vive en las preferencias de Pablo Opazo; si no está
cargado en la sesión, se pide antes de redactar material para clientes.

## Estado al 23-nov-2026

| Rama | Contenido | Estado |
|---|---|---|
| `claude/claude-md-docs-7gah4p` | Este CLAUDE.md | Rama por defecto. No existe `main` |
| `claude/edifica-meeting-questions-rjt7qs` | Preguntas a FISA para EDIFICA 2026 (cliente BEKA S.A.), .md y .docx | PR #1 cerrado el 23-nov-2026 como histórico: la reunión (27-ago) y la feria (20 al 22-oct) ya pasaron. La rama se conserva |

La rama de archivo no se borra: archivar es parte de publicar y nada se elimina.

## Calibrar: dónde está el material

El frente en curso es replantear **Calibrar** como diagnóstico de productividad
de personas y procesos: horas hombre por proceso, que se reinvierten y no se
recortan.

La versión vigente del PRD **no está en este repositorio**. Es la v6.0, escrita
el 23-nov-2026 en el Mac de Pablo, en la carpeta
`~/Documents/Claude/Projects/PRECISION/Calibrar/01 Producto/`. El archivo se
llama `Calibrar_PRD_v3_jul2026.md` aunque por dentro va en la v6.0, y
`qa_calibrar.py` y la cabina leen ese nombre, así que renombrarlo exige cambiar
esas rutas.

Reglas para trabajar aquí:
- No se reescribe el PRD en paralelo dentro del repositorio. Se parte de la v6.0.
- Si el PRD se trae al repositorio, se trae como copia de la v6.0 y se declara
  cuál es la fuente maestra.
- Los documentos de revisión del 23-nov-2026 (casos dorados de productividad y
  revisión de canon de la v6.0) esperan la revisión de Pablo y no se aplican sin
  su visto bueno.

## Convenciones

- Una rama por frente de trabajo; los PR se abren en borrador.
- Cada versión nueva de un documento archiva la anterior, renombrada
  `[SUPERADA — usar la vN]`.
- Fechas en formato `23-nov-2026`; nunca fechas relativas.
- Nunca se suben RUT, teléfonos ni nombres de contactos de clientes.
