# Ecommerce de Skin Care y Cosméticos --- VelvetSkin

## 1. Descripción General del Proyecto

El sistema consiste en una plataforma ecommerce especializada en la venta de productos para el cuidado de la piel y cosméticos. Tendra 2 roles: el de usuario y administrador. El rol de ususario Permitirá que puedan comprar productos, dejar reseñas, aplicar cupones de descuento, y realizar pagos en línea. El rol administrativo se encargara de la gestión del catálogo, pedidos, usuarios y promociones.

---

## 2. Objetivos

### Objetivo General
Desarrollar un ecommerce funcional, seguro y escalable que permita la venta de productos cosméticos y de cuidado de la piel de diferentes marcas a través de Internet.

#### Objetivos Específicos
- Permitir a los usuarios registrarse, iniciar sesión y gestionar su perfil.
- Ofrecer un catálogo organizado por categorias o marcas de los productos.
- Facilitar el proceso de compra mediante un carrito y un checkout.
- Integrar pasarelas de pago seguros.
- Permitir a los clientes dejar reseñas.
- Administrar productos, pedidos, usuarios y promociones desde el rol de administración.

---

## 3. Procesos Principales

| Proceso | Descripción |
|---------|-------------|
| Registro/Login | El usuario puede crear una cuenta o iniciar sesión para acceder a funciones avanzadas. |
| Productos | Consultar el catálogo, filtrar por tipo, categoría, etc. |
| Gestión del carrito | Agregar, quitar o modificar productos antes del pago. |
| Checkout | Confirmar dirección, aplicar cupones, elegir forma de pago. |
| Pagos | Interacción con una pasarela de pagos externa. |
| Creación de pedidos | Registro de la compra y cambio de estado (pendiente, pagado, enviado, entregado). |
| Gestión de reseñas | Dejar opiniones sobre productos comprados. |
| Administración | CRUD de productos, usuarios, pedidos y cupones. |
| Notificaciones | Envío de correos sobre confirmación, estado del pedido o promociones. |

---

## 4. Requerimientos Funcionales

1. **Gestión de usuarios y autenticacion**
   - Registro y login de clientes.
   - Gestión de perfil y direcciones.
   - Roles de usuario (cliente / administrador).

2. **Catálogo de productos**
   - Listado, búsqueda y filtrado de productos.
   - Detalles del producto: imágenes, ingredientes, tipo de piel, stock, precio.

3. **Carrito de compras**
   - Añadir/quitar productos.
   - Modificar cantidades.
   - Calcular total.

4. **Checkout y pedidos**
   - Selección de dirección de envío y método de pago.
   - Validación de stock.
   - Generación y almacenamiento del pedido.

5. **Pagos**
   - Integración de pasarela de pago(Paypal, etc)
   - Validación y confirmación del pago.

6. **Envios**
   - registrar direccion.
   - Asignar metodo de envio.
   - estado del envio.
   - actuañizar tracking.

7. **Cupones y descuentos**
   - Aplicación de cupones de descuento.
   - Gestión de cupones desde el rol de admin.
   
8. **Inventario**
   - ingreso y salid de stock.
   - alertar de stock bajo.
   
9. **Opiniones y valoraciones**
   - Publicación de reseñas por parte de usuarios autenticados.
   - Sistema de puntuación por estrellas.

10. **Notificaciones**
   - Emails automáticos al confirmar pedidos o cambiar el estado.

---

## 5. Requerimientos No Funcionales

| Categoría     | Requerimiento |
|---------------|---------------|
| **Rendimiento**     | El sistema debe responder en menos de 500ms para la mayoría de operaciones. |
| **Escalabilidad**   | Debe poder escalar horizontalmente con microservicios o contenedores. |
| **Seguridad**       | Uso de HTTPS, JWT, validación de datos. |
| **Mantenibilidad**  | Código modular, pruebas automatizadas, documentación clara. |
| **Disponibilidad**  | Alta disponibilidad, respaldos automáticos, monitoreo y recuperación ante fallos. |
| **Compatibilidad**  | Soporte para todos los navegadores modernos y dispositivos móviles. |
| **Portabilidad**    | Despliegue posible en cualquier infraestructura gracias a Docker y configuración por variables de entorno. |
| **Internacionalización** | Soporte para varios idiomas y monedas. (opcional según el mercado objetivo). |

