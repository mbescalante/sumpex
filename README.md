# Kooyo - The One

Este es un proyecto web para la marca **Kooyo**, que ofrece suplementos diseñados para mejorar la salud y el bienestar. El sitio web presenta un diseño limpio y moderno, destacando los productos principales, la historia de la marca y un sistema de pago funcional.

---

## Enlace al Proyecto

Puedes visitar la página en vivo aquí: [Kooyo - The One](https://mbescalante.github.io/sumpex/)

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
   - **Nuevo**: Los productos ahora tienen un botón de carrito funcional que permite agregar productos al carrito dinámico.

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

## Sistema de Carrito de Compras

### Funcionalidades del Carrito

- **Agregar Productos**:
  - Los usuarios pueden agregar productos al carrito haciendo clic en el ícono del carrito en cada tarjeta de producto.
  
- **Eliminar Productos**:
  - Los usuarios pueden eliminar productos del carrito desde el carrito lateral.

- **Cálculo Dinámico**:
  - El subtotal, el costo de envío y el total se calculan automáticamente en función de los productos en el carrito.

- **Costo de Envío**:
  - Envío gratuito para pedidos de 3 o más productos; de lo contrario, el costo de envío es de $5.

### Carrito Lateral

- El carrito se abre como un panel lateral al hacer clic en el botón del carrito en el encabezado.
- Incluye una lista de productos, un resumen del pedido y botones para proceder al pago o ver más detalles.

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

- **Carrito Dinámico**: Se agregó un carrito lateral funcional con cálculo automático de totales.
- **Fondo con Degradado**: Se utilizó un degradado para mejorar la estética de la sección `hero`.
- **Hover Interactivo**: Se añadieron efectos de hover en botones y estadísticas para mejorar la experiencia del usuario.
- **Carrusel de Testimonios**: Se implementó un carrusel para mostrar múltiples testimonios de manera dinámica.
- **Estadísticas Visuales**: Se añadieron estadísticas clave en la sección `hero` para destacar los logros de la marca.
- **Animaciones con AOS**: Se integraron animaciones suaves al desplazarse por la página.
- **Generación de PDF**: Se implementó un sistema para descargar la boleta de pago como PDF.
- **Botón de WhatsApp**: Se integró un botón con el ícono de WhatsApp para permitir que los usuarios realicen pedidos directamente por WhatsApp.

---

### Cambios Agregados:

1. **Carrito Dinámico**: Se incluyó una descripción detallada del carrito lateral y sus funcionalidades.
2. **Sistema de Pago**: Se añadieron detalles sobre el modal de pago y la generación de boletas en PDF.
3. **Mejoras Implementadas**: Se listaron las nuevas características y mejoras visuales.
4. **Futuras Mejoras**: Se incluyeron ideas para expandir el proyecto.

---

## Cómo Ejecutar el Proyecto

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/mbescalante/sumpex.git


Este formato está listo para ser copiado directamente a tu archivo `README.md`. La estructura es limpia y clara para facilitar la lectura en GitHub, y el contenido está dividido en secciones con los encabezados apropiados.
