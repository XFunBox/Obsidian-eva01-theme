# EVA-01 — Tema para Obsidian

**EVA-01 / NERV**  
*Dark technical workspace*

## Paleta visual

![Paleta de colores EVA-01: grafito oscuro, verde EVA, morado y texto claro](assets/paleta-eva-01.svg)

La paleta combina el fondo grafito `#15141D`, el verde EVA `#9DFC56`, el morado `#A48BFF` y el blanco suave `#E5E4EB`.

Tema oscuro inspirado en Ubuntu + KDE Plasma y la estética EVA-01: superficies grafito-morado, verde eléctrico para acciones y estados activos, morado para enlaces y secciones, y tipografía legible para sistemas y documentación técnica.

## Instalar

1. Cierra Obsidian (o reinícialo al terminar).
2. Crea `<tu_boveda>/.obsidian/themes/EVA-01/` y copia allí `manifest.json` y `theme.css`, que están en la raíz de este repositorio.
3. Abre **Ajustes → Apariencia → Temas** y selecciona **EVA-01**. Selecciona el esquema **Oscuro** en Apariencia.

Ejemplo para Linux, ejecutándolo desde el directorio en el que has descomprimido el ZIP:

```bash
mkdir -p "/ruta/a/tu/boveda/.obsidian/themes/EVA-01"
cp manifest.json theme.css "/ruta/a/tu/boveda/.obsidian/themes/EVA-01/"
```

> No modifica otros temas, plugins ni la barra flotante de KDE. No necesita fuentes de pago ni conexiones externas. Si ya tienes instalado **JetBrains Mono** e **Inter**, los usará; si no, emplea alternativas del sistema.

## Personalización rápida

Edita la copia instalada de `theme.css` para ajustar estos valores:

- `--interactive-accent`: verde principal `#9dfc56`.
- `--link-color`: morado de enlaces `#b4a2ff`.
- `--background-primary`: fondo central `#15141d`.
- `--file-line-width`: ancho para documentación (`850px`).

## Compatibilidad

Versión del tema **1.0.0**; requiere Obsidian **1.5.0 o posterior**, según `manifest.json`. El manifiesto permite su uso en escritorio y móvil; la apariencia móvil no se ha verificado en esta revisión. Pensado principalmente para escritorio Linux/KDE. El estilo es propio de Obsidian; no modifica temas de KDE, Konsole, Kitty ni aplicaciones ajenas. Algunos plugins con estilos personalizados pueden requerir ajustes adicionales.
