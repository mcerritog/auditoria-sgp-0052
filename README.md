# REG-SGP-0052 PWA — conversión del código Python/ReportLab

Esta versión toma como fuente el código ReportLab suministrado y convierte su checklist en una PWA instalable en Android.

## Se conservó
- Código REG-SGP-0052, versión 1 y fecha de creación 06/03/2026.
- Campos de auditor, fecha, proceso, semana, EDS, gerente y horario.
- Opción Auditoría / Revisión.
- Las 41 preguntas y sus pesos que realmente están definidos en el código fuente.
- Evaluación Sí / No / N/A.
- Seguimiento Mayor / Menor.
- Observaciones y campos de hallazgo: importe, responsable, fecha compromiso, soporte y acción.
- Resumen, firmas y reporte imprimible para guardar como PDF.

## Corrección importante
El código Python tenía `Total (Puntos) = 116` escrito manualmente, pero la suma de los pesos de sus 41 puntos es **115**. La PWA calcula el total automáticamente para evitar esa inconsistencia.

## Semáforo
95% o más: verde; 85% a 94.9%: amarillo; menos de 85%: rojo. Estos umbrales son configurables y no se presentan como política oficial.

## Publicación
Sube el contenido de este ZIP al nivel raíz del repositorio. Después: Settings > Pages > Deploy from a branch > main > /(root) > Save.

## PDF
La PWA no ejecuta Python ni ReportLab dentro del navegador. El reporte se construye en HTML y se abre con la función de impresión del navegador; en Android se puede seleccionar “Guardar como PDF”.
