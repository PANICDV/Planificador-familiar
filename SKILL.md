---
name: planificador-familiar
description: Organiza el tiempo de una pareja, familia (pareja + hijos/as) u hogar de varias personas con calendarios compartidos y personales en Google Calendar. Primero pregunta cuántas personas son, sugiere temas según el grupo, recomienda si conviene 1 proyecto con varios chats o menos, y deja un ciclo mensual / quincenal / semanal. Usar SIEMPRE que alguien quiera planificar en pareja o en familia, repartir tareas del hogar de forma justa, coordinar horarios entre varias personas, montar un sistema de planificación compartido, o crear recordatorios de mantenimientos y pagos a 2 años o más, aunque no mencione ".ics" ni "skill". Genera los archivos con la skill planificador-calendario-secciones.
---

# Planificador familiar

Una capa de **coordinación** sobre la skill `planificador-calendario-secciones`: decide
quiénes participan, qué temas se trabajan, cómo se reparten los chats y cuál es el ciclo de
planificación. La generación de los `.ics` la hace `planificador-calendario-secciones`
(si no está instalada, dilo y pide que la instale antes de generar archivos).

Idioma: el de la persona. Tono práctico y cálido, sin sermones.

## Flujo

### Paso 0. Preguntar cuántas personas son (SIEMPRE lo primero)
Un solo mensaje, lista numerada:
1. ¿Cuántas personas planifican? (adultos y niños/as por separado)
2. Edades de los hijos/as (decide si tienen planner propio o lo lleva un adulto).
3. ¿Quién va a usar el sistema directamente? (¿los dos adultos? ¿los adolescentes?)
4. ¿Qué calendario usa cada uno (Google, Apple, Outlook) y qué celular?
5. ¿Ya tienen calendarios o secciones creadas? (si sí, se reutilizan tal cual)

No sigas hasta tener esto. Si falta algo menor, estímalo y dilo.

### Paso 1. Sugerir temas según el grupo
Lee `references/temas.md`. Presenta una tabla corta con los temas que aplican al grupo
(no todos) y pide elegir. Cada tema elegido se convierte en una sección o en parte de una.
Ofrece también **temas libres** que la familia quiera añadir.

### Paso 2. Recomendar la estructura: 1 proyecto o n chats
Lee `references/estructura-chats.md`. Con el número de personas, recomienda:
- **1 proyecto** (contenedor con instrucciones y memoria compartida) y **cuántos chats** dentro.
- Qué genera cada chat (cada chat genera solo su sección; el chat combinado genera las compartidas).
Explica en 3–4 líneas por qué, y deja que la familia ajuste.

### Paso 3. Fijar secciones, ids y colores
Lee `references/secciones-base.md`. Propón la tabla de secciones (emoji + nombre, id,
color, quién la genera). **Una vez confirmadas no se cambian**: nombres, números de archivo y
colores se mantienen siempre, porque ya estarán creados en el calendario.

### Paso 4. Entrevista completa (primera vez)
Lee `references/entrevista.md`. Por bloques, listas numeradas, **separando las preguntas por
persona**. Incluye coincidencias: franjas libres de todos y cuántas sesiones juntos por semana
son realistas. En ciclos posteriores no repitas lo que ya sabes: confírmalo en una línea y
pregunta solo lo que cambió.

### Paso 5. Entregar las instrucciones del proyecto
Rellena `references/plantilla-instrucciones-proyecto.md` con lo acordado y entrégala lista
para pegar en las instrucciones del proyecto. Así cada chat nuevo arranca con las mismas reglas.

### Paso 6. Diseñar y generar
Aplica los principios de abajo y delega en `planificador-calendario-secciones` (un `.ics` por
sección; recordatorios recurrentes en su propio calendario). Entrega además la tabla resumen.

## Recordatorios a largo plazo (2 años o más)
Ofrece siempre el calendario **🔔 Recordatorios** para mantenimientos, pagos, renovaciones,
vehículo, salud preventiva y tecnología, con un horizonte de 2, 3 o más años. Lee
`references/recordatorios-largo-plazo.md`. Van en su propio archivo, con reglas de repetición,
y no se regeneran salvo que cambien (revisión anual).

## Ciclo de planificación
- **Mensual**: definir 2–3 metas por área compartida.
- **Cada dos semanas**: plan detallado día por día de los próximos 14 días, derivado de las metas.
- **Cada semana**: revisión corta juntos (30 min): avances y ajustes.
- **Al empezar cada ciclo**: pregunta qué cambió (horarios, compromisos fijos, energía, qué no
  se cumplió y por qué) antes de diseñar.
- **Al cerrar cada ciclo**: balance corto: qué se cumplió, qué se movió, qué ajustar.

## Principios de diseño
- No dedicar un día entero a un solo tema; alternar lo exigente con lo liviano.
- Sesiones juntos de 60–120 min, en horas en que todos los implicados tengan energía.
- Trámites con fecha incierta: opción A / opción B; el bloque no usado pasa a otro tema prioritario.
- Al menos un espacio flexible al día y tiempo libre en pareja/familia **sin agenda**.
- Hogar repartido de forma equilibrada: muestra una tabla de horas por persona y revisa si hay
  desbalance sostenido. Las tareas de los niños deben ser acordes a su edad.
- Alarmas solo en lo importante.
- Si un adulto tiene horario flexible, acomódalo al del otro.
- Si el plan no se cumplió, no culpes: pregunta por qué y reduce la carga antes de añadir.

## Entrega y actualizaciones
- Archivos `.ics` por sección + tabla resumen: horas por sección y por persona, y metas del ciclo.
- En actualizaciones, entrega solo las secciones que cambiaron y recuerda **borrar ese
  calendario y volver a crearlo** (mismo nombre y color) antes de importar, para no duplicar.
- Los recordatorios recurrentes no se regeneran salvo que cambien.
- Si se comparten calendarios con varias personas, recuerda volver a compartirlos tras recrearlos.

## Privacidad
Los datos de menores (colegio, horarios, ubicación) se usan solo para planificar. No pidas
documentos, direcciones exactas ni datos que el plan no necesite.
