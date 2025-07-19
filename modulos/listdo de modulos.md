
# Listado Modulos -- VelvetSkin

### 1. Módulo de Autenticación y Usuarios
**Descripción**: Gestiona el registro, login, y control de acceso de clientes y administradores.

**CRUD y funcionalidades clave**:
- Crear usuario (registro)
- Leer perfil de usuario
- Actualizar datos del usuario
- Eliminar usuario (opcional o desactivación)
- Login (autenticación con JWT o sesión)
- Validación de roles (admin, cliente)

---

### 2. Módulo de Productos
**Descripción**: Administra la información de los productos ofrecidos en el e-commerce.

**CRUD y funcionalidades clave**:
- Crear producto
- Listar productos (por página, categoría, búsqueda)
- Ver detalle de producto
- Actualizar información del producto
- Eliminar producto (o marcar como inactivo)
- Subir imágenes **
- Control de stock por producto

---

### 3. Módulo de Categorías y Subcategorías
**Descripción**: Permite agrupar los productos y facilitar su búsqueda.

**CRUD sugerido**:
- Crear categoría/subcategoría
- Listar categorías y subcategorías
- Actualizar nombre o estado
- Eliminar (o desactivar)

---

### 4. Módulo de Carrito de Compras
**Descripción**: Guarda los productos que el usuario desea comprar.

**Operaciones clave**:
- Agregar producto al carrito
- Ver carrito actual (por usuario)
- Actualizar cantidad de productos
- Eliminar productos del carrito
- Calcular total (subtotal + descuentos)

---

### 5. Módulo de Órdenes (Pedidos)
**Descripción**: Gestiona las compras realizadas por los usuarios.

**CRUD y funcionalidades clave**:
- Crear orden desde el carrito
- Listar órdenes por usuario o administrador
- Ver detalle de orden
- Actualizar estado (pendiente, en envío, entregado, cancelado)
- Cancelar orden (si aplica)

---

### 6. Módulo de Pagos
**Descripción**: Procesa y valida los pagos de los pedidos.

**Operaciones clave**:
- Registrar pago (simulado o real)
- Validar estado del pago
- Asociar pago con una orden
- Ver historial de pagos

---

### 7. Módulo de Envíos
**Descripción**: Controla la información de envío de cada pedido.

**Operaciones clave**:
- Registrar dirección de envío
- Asignar método de envío
- Ver estado del envío
- Actualizar tracking o estado logístico

---

### 8. Módulo de Cupones y Descuentos
**Descripción**: Permite aplicar promociones en los pedidos.

**CRUD sugerido**:
- Crear cupón (con condiciones)
- Ver y listar cupones disponibles
- Validar cupón en el carrito
- Aplicar descuento en el total

---

### 9. Módulo de Inventario
**Descripción**: Controla las entradas y salidas de productos.

**Operaciones clave**:
- Registrar ingreso o salida de stock
- Generar alertas de bajo stock
- Ver historial de movimientos

---

### 10. Módulo de Notificaciones
**Descripción**: Informa al usuario sobre cambios importantes.

**Ejemplos**:
- Envío de email tras compra o registro
- Notificaciones de estado de orden
- Confirmación de cambio de contraseña

---

