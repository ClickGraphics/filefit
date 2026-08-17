# FileFit — Roadmap

## Estado actual
- V0.2 pública en GitHub Pages
- JPG, PNG y WebP
- Conversión, redimensionado, crop ajustable y compresión por peso máximo
- Procesamiento 100% local
- Sin registro, servidor, base de datos ni APIs de pago
- Coste operativo objetivo: $0

## Próxima fase — adquisición orgánica
1. Crear landing pages útiles para intenciones específicas:
   - reducir imagen a 200 KB
   - reducir imagen a 100 KB
   - reducir imagen a 50 KB
   - redimensionar imagen a 600x600
   - comprimir imagen a tamaño específico
2. Reutilizar un único motor FileFit con presets, evitando duplicar lógica.
3. Añadir contenido único y útil a cada landing.
4. Conectar Google Search Console y enviar sitemap.
5. Medir impresiones, consultas, CTR y posiciones antes de ampliar el catálogo.

## Futuro — no implementar todavía
### Super Resolution / AI Upscaling
Investigar una herramienta para ampliar imágenes pequeñas a resoluciones mayores con mejora perceptual de detalle. Priorizar modelos abiertos con licencia compatible y ejecución client-side mediante WebGPU/WASM para conservar privacidad y coste operativo cercano a $0. Evaluar rendimiento móvil, tamaño del modelo, memoria y calidad antes de integrarlo.

## Principio del proyecto
Producto útil primero → tráfico real → datos → monetización → reinversión.
