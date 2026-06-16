Portfolio QA — Mauro Hidalgo
Tester de Software | QA Analyst
Merlo, Buenos Aires, Argentina
Maurohidalgo54@gmail.com
LinkedIn

 Sobre mí:
Soy Tester de Software con formación en QA Analyst (EducaciónIT) y experiencia práctica en pruebas funcionales, validación de APIs y bases de datos relacionales.
Este portfolio documenta mi trabajo de testing sobre BOT-ITA, un sistema real que desarrollé y estabilicé en producción para una fábrica de calzado de seguridad. A lo largo del proceso apliqué ciclos iterativos de detección de fallos, análisis de causa raíz, validación de correcciones y pruebas de regresión — sin saberlo en ese momento, estaba haciendo el trabajo de un QA.

 Proyectos
BOT-ITA — Sistema de gestión de pedidos e inventario vía WhatsApp
Descripción:
Sistema que permite registrar ventas, fabricación de lotes, pedidos y consultas de stock mediante mensajes de texto o audios en WhatsApp. El audio es transcripto por IA (Gemini API) y los datos impactan en una base de datos PostgreSQL.

 Stack técnico:
Python · Flask · PostgreSQL · WhatsApp Business API (Meta) · Gemini API · Ngrok
 Estado: En producción para un cliente real.


 Plan de Pruebas:
Alcance, criterios de aceptación, ambiente de pruebas

 Casos de Prueba
15 casos funcionales cubriendo flujos principales y casos borde

 Reporte de Bugs
3 bugs reales detectados, documentados y resueltos
Cobertura de pruebas

 Flujos testeados:
Registro de ventas (SALIDA) con datos completos e incompletos
Registro de fabricación (ENTRADA) simple y por lotes multi-talle
Creación, edición y cancelación de pedidos
Validación de stock insuficiente
Alerta de faltante y sugerencia de fabricación
Consultas de stock por modelo/talle y stock general
Cancelación de operación por usuario (flujo NO)
Comportamiento ante saturación de API externa (Gemini)
Clasificación correcta de mensajes fuera de contexto

 Bugs documentados:
2 bugs de severidad Alta (pérdida de datos en procesamiento de lotes)
1 bug de severidad Media (clasificación incorrecta de intención)
Los 3 resueltos 

 Habilidades aplicadas en este portfolio
Diseño y ejecución de casos de prueba funcionales
Identificación y documentación de bugs con pasos de reproducción
Testing de APIs REST con Postman
Validación de integridad de datos en PostgreSQL
Pruebas de casos borde y escenarios de error
Pruebas de regresión tras corrección de bugs

 Formación
Carrera QA Analyst — EducaciónIT (en curso · módulo QA Manual completado)
SQL — EducaciónIT (completado)
Portfolio en construcción — se irán agregando nuevos proyectos y documentación.