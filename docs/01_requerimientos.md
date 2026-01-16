# Requerimientos – Chatbot RRHH Somos Trenes

## Usuarios
- Empleados de Trenes Argentinos
- Perfil RRHH (visualización futura – mock)

---

## Requerimientos Funcionales

### Módulo 1 – Administración de Personal
- Consultar saldo disponible de todas las licencias del empleado.
- Visualizar detalle por tipo de licencia:
  - Vacaciones
  - Examen
  - Mudanza
  - Fallecimiento
  - Otras según convenio
- Iniciar solicitud de licencia desde el chatbot.
- Generar número de solicitud y estado.
- Consultar preguntas frecuentes sobre licencias.
- Mostrar fuente normativa (convenio / política RRHH).

---

### Módulo 2 – Búsquedas Internas
- Consultar cómo postularse a búsquedas internas.
- Informar pasos, requisitos y canales disponibles.
- Responder preguntas frecuentes del proceso.

---

### Módulo 3 – Servicio Médico
- Consultar preguntas frecuentes sobre licencias médicas.
- Informar plazos, certificados y pasos a seguir.
- Derivar a contacto humano en caso necesario (mensaje informativo).

---

### Módulo 4 – Soporte Somos Trenes
- Consultas sobre:
  - Visualización de recibos de sueldo
  - Fichadas
  - Diferencias entre versión web y mobile
  - Problemas de acceso
- Guías paso a paso.

---

## Requerimientos No Funcionales
- UX/UI consistente con la app Somos Trenes.
- Disponible en versión mobile y web.
- Respuestas claras, lenguaje simple.
- Backend desacoplado y escalable.
- Arquitectura preparada para integración SAP futura.
- Registro de logs y métricas básicas.
- Código documentado y versionado en GitHub.

---

## Seguridad y Privacidad (Demo)
- Uso de datos ficticios y sanitizados.
- Autenticación simulada mediante token JWT mock.
- No persistencia de datos reales.
