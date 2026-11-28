# Paso 2.5 — Requisitos de Interfaz

_Interacciones con otros sistemas o servicios mencionados o inferidos
(APIs, pasarelas de pago, servicios de notificación, etc.)._

| Sistema/Servicio externo | Tipo de interacción | Justificación/Origen |
|---|---|---|
| Servicio o motor OCR | Envío de documentos digitalizados y recepción del texto reconocido para facilitar la búsqueda de información. | Mencionado explícitamente en el modelo verbal. |
| Sistema gestor de bases de datos SQL | Almacenamiento y consulta de documentos, metadatos, usuarios, permisos y registros de auditoría. | Mencionado explícitamente en el modelo verbal. |
| Servicio de autenticación institucional | Validación de credenciales y, si corresponde, autenticación multifactor para controlar el acceso. | Inferido de los requisitos de seguridad y control de acceso. |
| Servicio de copias de seguridad | Envío de documentos y metadatos para respaldarlos, y recuperación de la información cuando sea necesario. | Inferido de la funcionalidad adicional propuesta en el Paso 1. |
| Sistema de archivos o almacenamiento digital | Almacenamiento y recuperación de los archivos digitalizados. | Inferido de la necesidad de conservar y consultar documentos digitales. |