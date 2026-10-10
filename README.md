# ShopGT - Repositorio del modelo de amenazas

Modelo de amenazas de una tienda en línea hipotética (caso académico de Seguridad en Aplicaciones), elaborado con OWASP Threat Dragon y la metodología STRIDE.

## Contenido

- `modelo/ShopGT-modelo-amenazas-v1.0.json`: proyecto de Threat Dragon con tres diagramas (Nivel 0, Nivel 1 y Nivel 2) y 35 amenazas cargadas.
- `diagramas/`: los tres DFD exportados como PNG.
- `docs/`: informe en PDF y matriz de riesgos y remediación en Excel.
- `CHANGELOG.md`: historial de versiones.

## Cómo abrir el modelo

1. Abrir OWASP Threat Dragon (aplicación de escritorio o versión web).
2. Elegir la opción de abrir un modelo existente y seleccionar el archivo JSON de la carpeta `modelo/`.
3. Si la herramienta ofrece migrar el modelo a su esquema más reciente, aceptar y revisar que los elementos queden ubicados como en los diagramas de `diagramas/`.
4. Ajustar posiciones si hace falta y volver a exportar las imágenes desde la herramienta.

## Cómo versionar los cambios

1. Guardar el JSON con el número de versión nuevo en el nombre (por ejemplo `ShopGT-modelo-amenazas-v1.1.json`).
2. Agregar una línea en `CHANGELOG.md` con fecha y cambio.
3. Si se usa Git, hacer un commit por cambio de arquitectura y una etiqueta (`git tag v1.1`) por cada versión consolidada.

## Estado

Versión 1.0, pendiente de validación técnica con Arquitectura y Desarrollo.
