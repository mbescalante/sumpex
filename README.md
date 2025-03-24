# Kooyo - The One

Este es un proyecto web para la marca **Kooyo**, que ofrece suplementos diseñados para mejorar la salud y el bienestar. El sitio web presenta un diseño limpio y moderno, destacando los productos principales, la historia de la marca y un sistema de pago funcional.

---

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:


---

## Tecnologías Utilizadas

- **HTML5**: Para la estructura del contenido.
- **CSS3**: Para el diseño y la presentación visual.
- **Bootstrap 5**: Para un diseño responsivo y componentes predefinidos.
- **AOS (Animate On Scroll)**: Para animaciones al desplazarse por la página.
- **Bootstrap Icons**: Para íconos en el sitio web.
- **JavaScript**: Para la funcionalidad interactiva.
- **jsPDF**: Para la generación de archivos PDF.
- **jsPDF-AutoTable**: Para crear tablas en los PDFs.

---

## Características

### Diseño Responsivo
El sitio está optimizado para verse correctamente en dispositivos móviles, tabletas y computadoras de escritorio.

### Secciones Principales
1. **Encabezado**:
   - Incluye el logotipo y un menú de navegación con enlaces a las secciones principales del sitio.
   - Los enlaces están configurados para desplazarse automáticamente a las secciones correspondientes.

2. **Hero Section**:
   - Presenta el mensaje principal de la marca con un diseño atractivo.
   - Incluye un fondo dinámico con degradado y estadísticas clave como clientes felices, reseñas positivas e ingredientes naturales.

3. **Productos**:
   - Una sección dedicada a mostrar los productos destacados con imágenes, descripciones y precios.
   - Incluye un diseño limpio y organizado con tarjetas de productos.

4. **Historia**:
   - Una sección que describe la historia de la marca y su misión.

5. **Proceso de Fabricación**:
   - Explica cómo se fabrican los productos, destacando la calidad y los ingredientes naturales.

6. **Equipo**:
   - Presenta al equipo detrás de la marca, destacando su experiencia y dedicación.

7. **Testimonios**:
   - Una sección con un carrusel que muestra opiniones de clientes satisfechos.
   - Cada testimonio está dentro de un cuadro con diseño moderno y estrellas de calificación.

8. **Sección de Suscripción**:
   - Permite a los usuarios suscribirse para recibir actualizaciones diarias.
   - Incluye un formulario con un campo de correo electrónico y un botón de envío.

9. **Pie de Página**:
   - Contiene enlaces a las redes sociales, un menú adicional y categorías clave.
   - Incluye información de derechos de autor.

---

## Sistema de Pago

### Modal de Pago
- Los usuarios pueden seleccionar entre tres métodos de pago:
  1. **Tarjeta de Crédito**: Permite ingresar los datos de la tarjeta, nombre, correo y número de documento.
  2. **Efectivo**: Solicita el nombre, correo y número de documento.
  3. **Transferencia Bancaria**: Solicita los datos bancarios, nombre, correo y número de documento.

### Modal de Boleta
- Después de confirmar el pago, se muestra un modal con los detalles de la boleta:
  - Método de Pago
  - Monto
  - Nombre del Cliente
  - Correo Electrónico
  - Número de Documento

### Generación de PDF
- Los usuarios pueden descargar la boleta como un archivo PDF.
- El PDF incluye:
  - Información de la empresa (nombre, RUC, dirección)
  - Detalles del cliente
  - Detalles del pago
  - Tabla de resumen con subtotal, IGV (18%) y total
  - Mensaje de agradecimiento en el pie de página

---

## Mejoras Implementadas

- **Fondo con Degradado**: Se utilizó un degradado para mejorar la estética de la sección `hero`.
- **Hover Interactivo**: Se añadieron efectos de hover en botones y estadísticas para mejorar la experiencia del usuario.
- **Carrusel de Testimonios**: Se implementó un carrusel para mostrar múltiples testimonios de manera dinámica.
- **Estadísticas Visuales**: Se añadieron estadísticas clave en la sección `hero` para destacar los logros de la marca.
- **Animaciones con AOS**: Se integraron animaciones suaves al desplazarse por la página.
- **Generación de PDF**: Se implementó un sistema para descargar la boleta de pago como PDF.

---

## Cómo Ejecutar el Proyecto

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/mbescalante/sumpex.git
