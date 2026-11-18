# Piel y Deporte

Aplicación web propuesta para el área de Dermatología y Deporte de la Fundación Piel Sana de la AEDV.
Publicada en: https://25clara25-hue.github.io/piel-y-deporte/

## Archivos
- `index.html`: aplicación completa. El script está dividido en bloques: `CONFIG`, contenidos clínicos (`CONTENT`), proveedor UV (`UVProviders`) y reglas de recomendación (`RULES`).
- `sw.js`: caché mínima para abrir los contenidos sin conexión.

## Estado técnico (uso interno)
| Función | Estado |
|---|---|
| Plan de protección, formación, listas, guía de lesiones, encuesta | Operativo |
| Datos UV | Open-Meteo (predicción por modelo). Fuente pendiente de validar por la Fundación; valorar AEMET. |
| Ejemplo UV simulado | Demostración, siempre etiquetado |
| Envío de encuesta | Lo envía el participante desde su app de correo (mailto) a `CONFIG.surveyEmail`, tras información y consentimiento. Texto informativo y base jurídica pendientes de validar (Fundación/DPD). |
| Recogida centralizada automática | Desactivada |
| Solicitud de cita | No configurada (`CONFIG.appointmentService`) |
| Contenidos clínicos | Pendientes de revisión clínica (`CONTENT.review`) |
| Enlaces Fundación Piel Sana / UV-Derma | Pendientes de confirmar |
| Fotografías | NCI (www.cancer.gov), dominio público, enlazadas desde CDC PHIL |
| Logotipos oficiales | No incluidos |
