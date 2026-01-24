# Política de Divulgación Responsable y Coordinada (CVD) - OSC

Esta política establece el protocolo oficial de **Open Security Collective (OSC)** para la identificación, reporte y publicación de vulnerabilidades de seguridad. Nuestro objetivo es minimizar el riesgo para los usuarios finales y ayudar a las organizaciones a fortalecer sus sistemas de manera colaborativa y ética.

## 1. Compromiso del Investigador
Cualquier miembro o colaborador de OSC que identifique una vulnerabilidad debe adherirse estrictamente a los siguientes principios:

* **No Dañar:** Evitar cualquier acción que pueda degradar el servicio, interrumpir procesos de negocio o comprometer la integridad de datos de terceros.
* **Privacidad de Datos:** Si durante la investigación se accede accidentalmente a datos sensibles o personales, se debe detener la actividad de inmediato, eliminar cualquier copia local y notificar el incidente a la entidad afectada.
* **Proporcionalidad:** Solo se debe realizar la Prueba de Concepto (PoC) mínima necesaria para demostrar la existencia del fallo sin comprometer la estabilidad del sistema.

## 2. Procedimiento de Reporte
1.  **Identificación de Canal:** Se priorizará el uso del archivo `security.txt` del dominio afectado o los contactos de seguridad oficiales de la organización.
2.  **Notificación Inicial:** OSC enviará un informe técnico preliminar de forma privada y, de ser posible, mediante canales de comunicación cifrados (PGP/Signal).
3.  **Triaje Interno:** Antes de enviar un reporte bajo el sello de OSC, el equipo de **VDP-Triage** validará la criticidad del fallo utilizando el estándar **CVSS v3.1/v4.0**.

## 3. Plazos de Corrección (Timeline)
OSC sigue los estándares internacionales de la industria para garantizar un tiempo justo de reparación:

* **90 días calendario:** Plazo estándar para la mayoría de las vulnerabilidades.
* **7 días:** Para vulnerabilidades que estén siendo explotadas activamente en el "mundo real" (zerodays bajo ataque).
* **Extensiones:** OSC es flexible. Si la entidad demuestra progreso constante y la solución técnica es compleja, se pueden acordar extensiones de 15 a 30 días adicionales.

## 4. Publicación y Transparencia
* **Divulgación Coordinada:** OSC no publicará detalles técnicos, análisis de causa raíz o códigos de explotación hasta que el fallo haya sido corregido satisfactoriamente.
* **Reconocimiento y CVE:** Se solicitará a la entidad el permiso para mencionar el hallazgo en el portafolio de OSC y, cuando corresponda, se gestionará la asignación de un identificador **CVE** (Common Vulnerabilities and Exposures).
* **Divulgación Forzosa (Excepción):** Si una organización ignora repetidamente las comunicaciones o se niega a reparar un fallo crítico que pone en riesgo masivo a los usuarios, OSC se reserva el derecho de publicar una alerta limitada para proteger a la población, tras agotar todas las instancias de diálogo.

## 5. Puerto Seguro (Safe Harbor)
OSC opera bajo la premisa de que la seguridad es un esfuerzo común. Solo operaremos de manera oficial con organizaciones que garanticen un **"Puerto Seguro"**, comprometiéndose a:

* No iniciar acciones legales civiles o penales contra los investigadores de OSC que cumplan con esta política.
* Considerar la investigación como "actividad autorizada" bajo los términos de la **Ley N° 21.459 (Chile)** y normativas internacionales equivalentes.

---
**Control de Versiones**
| Versión | Fecha | Descripción | Autor |
| :--- | :--- | :--- | :--- |
| 1.0.0 | 23-01-2026 | Publicación inicial del protocolo CVD | Core Team OSC |
