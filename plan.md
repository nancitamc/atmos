# Plan de implementación — Certificado ATMOS

## Enfoque

Conservar la línea gráfica del formulario existente: barra superior azul marino, azul/cian ATMOS, tipografía Manrope, páginas tamaño carta con encabezado degradado, superficies blancas y navegación por hojas. Reemplazar la estructura actual de portada/secciones por un documento de cuatro páginas más anexos.

## Funcionalidad

- Página 1 con selector entre Formato Estándar y Formato Entidad de Salud.
- Formato Estándar: campos de entidad, datos de contacto opcionales, próximo control opcional, servicios, tabla editable con columnas/filas ajustables, observaciones y nota opcionales, y área amplia para firma.
- Formato Entidad de Salud: campos de entidad intervenida, NIT, dirección, fechas, horarios y áreas tratadas/productos utilizados opcionales.
- Página 2 basada en `Recomendaciones.jpg`.
- Página 3 basada en `Diagnóstico.jpg`.
- Página 4 basada en `Certificacion Secretaría de Salud.jpeg`.
- Anexos al final: imágenes renderizadas, PDF embebido cuando el navegador lo permite y otros archivos identificados con nombre/tipo.
- Impresión/PDF: controles de edición, casillas vacías y campos sin contenido desaparecen; el texto escrito y las opciones marcadas quedan como reporte limpio.

## Estructura

- `Certificado_Formulario.html`: aplicación autocontenida, estilos, markup de las cuatro páginas y comportamiento.
- `Modelo Estándar.jpg`, `Modelo Entidad Salud.jpg`, `Recomendaciones.jpg`, `Diagnóstico.jpg`, `Certificacion Secretaría de Salud.jpeg`: referencias visuales locales.
- `Logo/atmos1-horizontal.svg`: marca ATMOS reutilizada en la interfaz.
