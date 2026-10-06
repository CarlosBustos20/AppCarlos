# Aplicación de Pedidos de Comida - Android (AppCB)

## Resumen del Proyecto
Aplicación móvil desarrollada en Android Studio para la gestión de pedidos, consulta de historial y contacto con soporte técnico, integrando Intents implicitos y explicitos.

- **Versión de Android Min SDK:** API  31(Android 12.0)


---

## Listado de Intents Implementados

### 1. Intents Explícitos (3)
1. **Navegación a Confirmación de Pedido (`PedidoConfi`):**
   - **Acción:** Abre la actividad de confirmación al presionar "Realizar Pedido".
2. **Navegación a Historial (`Historial`):**
   - **Acción:** Abre la actividad del historial de compras.
3. **Navegación a Centro de Ayuda (`Ayuda`):**
   - **Acción:** Abre la pantalla de soporte técnico.

### 2. Intents Implícitos (5)
1. **Ver Ubicación del Pedido (Mapa):**
   - **Acción:** Abre Google Maps o app de mapas usando la URI `geo:0,0?q=...`.
2. **Ver Menú en Línea (Navegador Web):**
   - **Acción:** Abre la página web del menú utilizando `Intent.ACTION_VIEW`.
3. **Llamar al Restaurante (Marcador Telefónico):**
   - **Acción:** Abre el teclado de llamadas utilizando `Intent.ACTION_DIAL`.
4. **Enviar un Correo (Cliente de Email):**
   - **Acción:** Abre la app de correo utilizando `Intent.ACTION_SENDTO`.
5. **Captura de Fotografía (Cámara):**
   - **Acción:** Solicita permiso `CAMERA` en tiempo de ejecución y ejecuta `MediaStore.ACTION_IMAGE_CAPTURE`.
