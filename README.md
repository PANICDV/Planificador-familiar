# planificador-familiar

Skill de Claude para organizar el tiempo de una **pareja**, una **familia con hijos/as** o un
**hogar de varias personas**, con calendarios personales y compartidos en Google Calendar
(o Apple / Outlook).

## Qué hace
1. **Pregunta cuántas personas son** (adultos e hijos/as) y sus edades.
2. **Sugiere temas** según el grupo: aprender y crear, hogar, tecnología, hijos, finanzas…
3. **Recomienda la estructura**: 1 proyecto y cuántos chats usar según el número de personas.
4. Fija **secciones con colores** (no cambian después) y entrega **instrucciones del
   proyecto** listas para pegar.
5. Corre un **ciclo**: metas mensuales → plan quincenal → revisión semanal → balance.
6. Reparte el hogar de forma **justa**, con tabla de horas por persona.
7. Arma **recordatorios de mantenimientos y pagos a 2 años o más** (hogar, vehículo, pagos,
   renovaciones, salud, tecnología) en un calendario aparte.

## Requisito
 Funciona junto con la skill
   [`planificador-calendario-secciones`](https://github.com/PANICDV/planificador-calendario-secciones),
   que genera los archivos `.ics` (uno por sección, cada uno con su color). Instala ambas.

## Instalación
- **Claude (web/escritorio)**: descarga el ZIP de esta carpeta y súbelo como skill en la
  configuración de Claude (la ruta exacta puede variar según tu versión y plan).
- **Claude Code**: copia la carpeta `planificador-familiar/` en `~/.claude/skills/`
  (o en `.claude/skills/` de tu proyecto).

## Uso rápido
Escribe, por ejemplo:
> Quiero organizar el tiempo de mi familia: somos 2 adultos y 2 hijos.

La skill preguntará cuántas personas son y seguirá el flujo.

## Estructura
```
planificador-familiar/
├── SKILL.md
├── README.md
└── references/
    ├── temas.md
    ├── estructura-chats.md
    ├── secciones-base.md
    ├── entrevista.md
    ├── recordatorios-largo-plazo.md
    └── plantilla-instrucciones-proyecto.md
```

## Privacidad
Esta skill no incluye datos personales. Si la usas con menores, comparte solo lo necesario
para planificar (horarios y actividades), no direcciones ni documentos.

## Licencia
MIT (ver `LICENSE`).
