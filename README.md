# Prueba Técnica Black Comet - Calculadora de Migración

Implementación de una calculadora de precios dinámica para migraciones de plataforma, desarrollada como una Sección de Shopify personalizada.

## Archivos Clave
- **`sections/migration-calculator.liquid`**: Contiene la estructura HTML, la configuración del esquema Liquid y la lógica JavaScript (algoritmo de precios, envío AJAX, validación).
- **`assets/migration-calculator.css`**: Hoja de estilos dedicada para la calculadora, asegurando un diseño responsive y premium.

## Funcionalidades Implementadas
- **Precios Dinámicos**: Estimación de costes en tiempo real basada en el número de Clientes, Pedidos y Productos.
- **Ajustes Geolocalizados**: Detección automática del país del usuario para aplicar tasas de conversión y multiplicadores de precio específicos.
- **Envío de Formulario AJAX**: Experiencia "single-page" fluida con un fallback a envío nativo para una gestión de errores robusta (soporte para CORS/401).
- **Validación Inteligente**: Feedback visual en tiempo real para campos obligatorios, incluyendo inputs inteligentes para el prefijo telefónico.
- **Diseño Responsive**: Enfoque Mobile-first utilizando CSS Grid y Flexbox.
