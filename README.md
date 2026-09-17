# MotorPartsExpress

Aplicación web de comercio electrónico especializada en la venta de repuestos para vehículos.

MotorPartsExpress permite consultar un catálogo de productos, buscar y filtrar repuestos, gestionar un carrito de compra, realizar pedidos y administrar perfiles de clientes y vendedores.

## Demo

Prueba la aplicación publicada en GitHub Pages:

[https://pistachopower.github.io/](https://pistachopower.github.io/)

## Repositorio

[https://github.com/Pistachopower/Pistachopower.github.io](https://github.com/Pistachopower/Pistachopower.github.io)

## Funcionalidades

- Página de inicio con categorías y productos destacados.
- Catálogo de repuestos con búsqueda y filtros.
- Detalle de producto y productos relacionados.
- Lista de deseos.
- Carrito de compra con actualización de cantidades.
- Registro, inicio de sesión y recuperación de contraseña.
- Valoraciones y comentarios de productos.
- Proceso de checkout con dirección de envío.
- Gestión de pedidos y devoluciones.
- Métodos de pago e integración con PayPal.
- Perfil de cliente con datos personales, pedidos, valoraciones, pagos y lista de deseos.
- Panel de vendedor con gestión de productos, pedidos, clientes, devoluciones y comentarios.
- Chatbot de atención al usuario.
- Seguimiento de eventos y acciones dentro de la aplicación.

## Tecnologías

- [Vue 3](https://vuejs.org/)
- [Vue Router](https://router.vuejs.org/)
- [Pinia](https://pinia.vuejs.org/)
- [Axios](https://axios-http.com/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [PostHog](https://posthog.com/)
- [Vue CLI](https://cli.vuejs.org/)
- [pnpm](https://pnpm.io/)

## Requisitos

- Node.js
- pnpm
- Backend de la aplicación disponible y correctamente configurado

Las operaciones de autenticación, catálogo, carrito, pedidos y pagos utilizan la API del backend.

## Instalación

Clona el repositorio y accede a la carpeta del proyecto:

```bash
git clone https://github.com/Pistachopower/Pistachopower.github.io.git
cd Pistachopower.github.io
```

Instala las dependencias:

```bash
pnpm install
```

## Desarrollo

Inicia el servidor de desarrollo con recarga automática:

```bash
pnpm run serve
```

La aplicación estará disponible normalmente en `http://localhost:8080`.

## Scripts disponibles

| Comando | Descripción |
| --- | --- |
| `pnpm run serve` | Inicia el servidor de desarrollo. |
| `pnpm run build` | Genera la compilación optimizada para producción en `dist/`. |
| `pnpm run lint` | Analiza el código con ESLint. |
| `pnpm run deploy` | Compila y publica `dist/` en GitHub Pages. |

## Estructura principal

```text
src/
├── assets/          # Imágenes y recursos estáticos
├── components/      # Componentes y vistas de la aplicación
├── models/          # Modelos de datos
├── router/          # Configuración de Vue Router
├── services/        # Comunicación con la API y seguimiento de eventos
├── stores/          # Estado global gestionado con Pinia
└── views/           # Vistas principales
```

## Despliegue

El proyecto incluye un script para publicar en GitHub Pages:

```bash
pnpm run deploy
```

Este comando compila la aplicación, crea `dist/404.html` a partir de `dist/index.html` para mantener las rutas de Vue Router y publica la carpeta `dist/`.

También se incluye documentación para el despliegue mediante AWS y Nginx en [Documentacion/DespliegueFrontendAWS.md](Documentacion/DespliegueFrontendAWS.md).

## Documentación adicional

La carpeta `Documentacion/` contiene diagramas y explicaciones de los principales flujos funcionales de la aplicación.

## Autor

Desarrollado por [Pistachopower](https://github.com/Pistachopower).