# Biblioteca gráfica Volcán · Mailings

Repositorio público de recursos gráficos para correos corporativos creados en VS Code y enviados desde Brevo.

## Carpetas

- `iconos/`: iconos e ilustraciones SVG originales
- `banners/`: cabeceras y fotografías de los mailings
- `footers/`: pies de correo y elementos de cierre
- `logos/`: logotipos autorizados para distribución pública
- `otros/`: recursos complementarios

## Cómo subir un recurso

En GitHub, entra en la carpeta adecuada → **Add file → Upload files** → arrastra tus archivos → **Commit changes**.

Usa nombres en minúsculas, sin espacios ni acentos. Ejemplo: `iconos/regalo-navidad.svg`.

## URLs para Brevo

Una vez activado **Settings → Pages → Deploy from a branch → main → /(root)**, un archivo como `iconos/regalo-navidad.svg` tendrá una URL pública de esta forma:

`https://carlos-f-g.github.io/volcan-mailing-assets/iconos/regalo-navidad.svg`

Se inserta en el HTML:

```html
<img src="https://carlos-f-g.github.io/volcan-mailing-assets/iconos/regalo-navidad.svg"
     width="70" height="70" alt="Regalo de Navidad"
     style="display:block;border:0;margin:0 auto;">
```

**Compatibilidad:** Brevo puede utilizar una URL pública HTTPS. Sin embargo, algunos clientes de correo, especialmente Outlook, no muestran archivos SVG aunque estén alojados externamente. Verifica los correos con envíos de prueba antes de enviarlos masivamente. Si decides usar formatos alternativos para algunos clientes, conserva el SVG como archivo maestro.

**Privacidad:** el contenido de este repositorio y de GitHub Pages es público. No subas datos personales, documentos internos, fotografías sin autorización ni recursos cuya publicación no esté aprobada.

## Convenciones

- Nunca sobrescribas iconos utilizados en mailings antiguos si necesitas mantenerlos exactamente igual: crea versiones con sufijo `-v2`, `-v3`, etc.
- Evita renombrar o mover archivos usados en correos enviados, porque se romperían sus enlaces.
- Mantén los archivos SVG optimizados y con `viewBox`.
