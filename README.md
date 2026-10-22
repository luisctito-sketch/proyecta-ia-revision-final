# PROYECTA-IA — REVISIÓN FINAL INTEGRAL

## Nombre recomendado del repositorio GitHub
`proyecta-ia-revision-final`

URL esperada al activar GitHub Pages:
`https://luisctito-sketch.github.io/proyecta-ia-revision-final/`

## Propósito
Módulo final de control metodológico y técnico previo al envío del Proyecto de Grado al docente.

El estudiante debe cargar el archivo **.DOCX completo y final**. La herramienta procesa el Word en el navegador y emite una ponderación preliminar sobre 100 puntos.

### Umbral
- **90/100 o más y sin bloqueos críticos:** APTO PARA REVISIÓN DOCENTE.
- **Menos de 90:** debe corregirse y volver a revisarse antes de enviarlo.

## Certificado
Cuando el documento supera 90/100 se habilita un PDF de dos páginas denominado:
**Certificado de revisión preliminar PROYECTA-IA**.

El certificado:
- muestra el puntaje;
- identifica el archivo revisado mediante SHA-256;
- no reemplaza aval del tutor, carta de conformidad, aprobación institucional ni evaluación del tribunal;
- incluye en el reverso los controles que quedan a cargo del docente.

## Entrega posterior al docente
El estudiante debe remitir por WhatsApp:
1. Word final;
2. certificado PROYECTA-IA;
3. C.I.;
4. Registro Universitario;
5. foto/escaneo de la carta aval del tutor dirigida al HCC indicando que el Proyecto de Grado fue cumplido.

## Acceso centralizado
Carga el mismo archivo central de autorización:
`https://luisctito-sketch.github.io/proyecta-ia-acceso/access.js`

No es necesario mantener una lista de C.I. dentro de este repositorio.

## Archivos
- `index.html`
- `styles.css`
- `app.js`
- `RUBRICA_REVISION_FINAL_100_PUNTOS.md`
- `CRITERIOS_CERTIFICADO.md`
- `README.md`

## Librerías web
El portal usa JSZip para inspeccionar el DOCX y jsPDF para generar el certificado. Ambas librerías se cargan desde CDN.

## Limitación metodológica importante
La puntuación es un control automático preliminar. No puede comprobar por sí sola la autenticidad física del prototipo, la veracidad de una medición, la existencia real de cada fuente bibliográfica, el gramaje del papel o el juicio profesional final del docente.
