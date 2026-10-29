# Recordatorios a largo plazo (2 años o más)

Los recordatorios recurrentes (mantenimientos, pagos, renovaciones) van en el calendario
**🔔 Recordatorios**, en su propio archivo. Pueden cubrir 2, 3 o más años de una sola vez,
porque no dependen del ciclo quincenal y **no se regeneran salvo que cambien**.

## Cuándo ofrecerlo
Al armar las secciones (paso 3), ofrece siempre el calendario de recordatorios y pregunta:
"¿Quieren que lo armemos para 2 años, 3 años o más?". Si dudan, propón 2 años y se extiende
después.

## Qué suele ir (pregunta cuáles aplican)
| Tipo | Ejemplos | Frecuencia típica |
|---|---|---|
| 🔧 Mantenimiento del hogar | Limpieza de tanque, fumigación, revisión eléctrica, filtros, terma, goteras | Cada 3, 6 o 12 meses |
| 🚗 Vehículo | Cambio de aceite, revisión técnica, seguro, SOAT / impuestos, llantas | Por km (estimar en meses) o anual |
| 💳 Pagos | Servicios, alquiler/hipoteca, colegio, suscripciones, seguros, impuestos | Mensual, trimestral, anual |
| 📄 Renovaciones y trámites | Documentos, licencias, dominios, garantías | Anual o según vencimiento |
| 🩺 Salud preventiva | Chequeos, vacunas, citas dentales, veterinario de mascotas | Anual / semestral |
| 🌱 Plantas y mascotas | Riego, abonado, desparasitación | Cada N días / semanas |
| 💾 Tecnología | Respaldos, revisión del NAS, renovar antivirus o dominios | Mensual / anual |

## Cómo definirlos
1. Para cada recordatorio pide: **qué**, **cada cuánto** (cada N días, cada día X del mes,
   cada N meses, una vez al año) y **desde cuándo**.
2. Si la fecha exacta es incierta (por ejemplo, una renovación), crea el recordatorio
   anticipado (30 días antes) y otro en la fecha estimada.
3. **Alarmas solo en lo importante**: pagos con vencimiento y trámites con fecha límite
   llevan alarma; la limpieza rutinaria no.
4. Escribe en el título la **persona responsable** si el hogar tiene varias.
5. Los pagos con monto fijo pueden incluir el monto en la descripción, pero **no pidas ni
   guardes números de cuenta, tarjetas ni claves**.

## Horizonte y actualizaciones
- Para periodos largos, un solo archivo `R_recordatorios.ics` con todo el horizonte.
- Revisa los recordatorios **una vez al año** (o cuando cambie algo grande: mudanza, nuevo
  auto, nuevo hijo/a) y regenera el archivo solo si hubo cambios.
- Si cambia, recuerda: borrar el calendario 🔔, crearlo con el mismo nombre y color, importar
  y volver a compartirlo.
- Para horizontes de más de 2 años, avisa que Google puede tardar en mostrar muchos eventos
  repetidos y que conviene usar reglas de repetición (RRULE) en vez de un evento por fecha.
