
# Biblioteca gráfica Volcán · Mailings

Repositorio público destinado exclusivamente al almacenamiento, organización y distribución de recursos gráficos utilizados en las comunicaciones corporativas de Volcán.

Este espacio facilita la integración de imágenes, iconos, ilustraciones y elementos visuales en correos HTML desarrollados en VS Code y distribuidos mediante Brevo.

---

## Propósito y alcance

Este repositorio funciona como una biblioteca centralizada de recursos visuales para apoyar el desarrollo de piezas de comunicación corporativa.

Su utilización está limitada a:

- Iconos e ilustraciones gráficas.
- Banners y cabeceras para mailings.
- Elementos visuales de identidad corporativa.
- Pies de correo y recursos complementarios.
- Imágenes autorizadas para comunicaciones internas o externas.

El repositorio no está destinado al almacenamiento de documentos de trabajo, información administrativa, bases de datos ni antecedentes internos de la compañía.

## Seguridad y confidencialidad de la información

**Compromiso con la protección de la información corporativa**

Al tratarse de un repositorio público, todos los recursos almacenados deben estar previamente autorizados para su publicación y distribución.

No está permitido almacenar, compartir ni exponer:

- Información confidencial o estratégica de Volcán.
- Datos personales de colaboradores, clientes o proveedores.
- Documentos internos o información administrativa.
- Bases de datos, listas de contactos o correos electrónicos privados.
- Credenciales, contraseñas, claves API o configuraciones sensibles.
- Información comercial, financiera o contractual reservada.
- Fotografías o material gráfico sin autorización de publicación.

**Principio de uso responsable**

Todo contenido incorporado debe cumplir con los lineamientos de identidad corporativa, confidencialidad y seguridad de la información de Volcán.

El objetivo es mantener un entorno de recursos gráficos organizado, eficiente y seguro, sin comprometer información de carácter reservado.

La publicación de un archivo en este repositorio implica que podrá ser consultado públicamente a través de GitHub y GitHub Pages.

---

## Estructura del repositorio

Las carpetas están organizadas según el tipo de recurso:

- `iconos/`: iconos e ilustraciones en PNG y SVG.
- `banners/`: cabeceras y fotografías para mailings.
- `footers/`: pies de correo y elementos de cierre.
- `logos/`: logotipos autorizados para distribución pública.
- `otros/`: recursos gráficos complementarios.

Esta estructura permite mantener los archivos organizados y facilitar su reutilización en diferentes campañas.

## Formatos gráficos recomendados

### PNG

Formato recomendado para iconos, ilustraciones, logotipos y otros elementos gráficos utilizados en correos electrónicos.

Ventajas:

- Amplia compatibilidad con Gmail, Outlook y otros clientes de correo.
- Permite fondos transparentes.
- Conserva buena definición visual.
- Se integra directamente mediante enlaces HTTPS.

### SVG

Formato vectorial utilizado para conservar los recursos gráficos originales.

Ventajas:

- Calidad independiente de la resolución.
- Permite editar y modificar los recursos.
- Generalmente ofrece archivos livianos para ilustraciones simples.

**Importante:** algunos clientes de correo, especialmente Outlook, presentan limitaciones para visualizar SVG. Por esta razón, se recomienda utilizar PNG en los mailings finales y conservar SVG como archivo maestro cuando corresponda.

### JPEG

Formato recomendado para fotografías y banners que no requieren transparencia.

---

## Cómo subir un recurso

1. Accede al repositorio en GitHub.
2. Ingresa a la carpeta correspondiente.
3. Selecciona **Add file → Upload files**.
4. Arrastra los archivos que deseas incorporar.
5. Confirma la operación mediante **Commit changes**.

Antes de publicar, verifica que los archivos estén autorizados para su difusión.

### Convenciones de nombres

Utiliza nombres descriptivos, en minúsculas, sin espacios ni caracteres especiales.

Ejemplos:

- `iconos/regalo-navidad.png`
- `iconos/calendario.png`
- `iconos/ubicacion.png`
- `banners/fiesta-navidad.jpg`
- `footers/bienestar-volcan.png`

---

## URLs para Brevo

Los recursos se distribuyen públicamente mediante GitHub Pages.

Configuración del repositorio:

**Settings → Pages → Deploy from a branch → main → /(root)**

Una vez publicados, los archivos pueden utilizarse mediante enlaces HTTPS.

### Ejemplo de URL

Archivo:

`iconos/regalo-navidad.png`

URL pública:

`https://carlos-f-g.github.io/volcan-mailing-assets/iconos/regalo-navidad.png`

### Integración HTML

```html
<img
  src="https://carlos-f-g.github.io/volcan-mailing-assets/iconos/regalo-navidad.png"
  width="70"
  height="70"
  alt="Regalo de Navidad"
  style="display:block;border:0;margin:0 auto;"
>
```

La URL debe coincidir exactamente con el nombre y la ubicación del archivo dentro del repositorio.

## Compatibilidad con correos electrónicos

Los recursos alojados en GitHub Pages pueden utilizarse mediante URLs públicas HTTPS en los HTML de Brevo.

Para mejorar la compatibilidad:

- Prioriza PNG para iconos e ilustraciones.
- Utiliza JPEG para fotografías.
- Conserva SVG como formato vectorial original.
- Optimiza el peso de los archivos.
- Incluye textos alternativos mediante `alt`.
- Realiza pruebas en Gmail, Outlook y dispositivos móviles.

La visualización de imágenes externas puede depender de la configuración de seguridad del destinatario.

---

## Mantenimiento y buenas prácticas

- Mantén una estructura ordenada por categorías.
- Utiliza exclusivamente recursos autorizados.
- Evita incorporar archivos duplicados o innecesarios.
- Optimiza imágenes antes de publicarlas.
- Conserva los originales editables cuando corresponda.
- No sobrescribas recursos utilizados en campañas anteriores si necesitas preservar sus versiones.
- Utiliza sufijos `-v2`, `-v3`, etc., para nuevas versiones.
- Evita mover o renombrar archivos utilizados en correos enviados, ya que sus enlaces podrían dejar de funcionar.
- Verifica periódicamente que los enlaces públicos sigan disponibles.
- Revisa que ningún archivo contenga metadatos o información sensible antes de subirlo.

---

## Uso exclusivo

**Este repositorio tiene una finalidad exclusivamente gráfica y comunicacional.**

No constituye un repositorio oficial de documentación interna, ni un espacio autorizado para almacenar o divulgar información confidencial de la compañía.

Todos los recursos publicados deben estar destinados a su uso visual y contar con la autorización correspondiente.

---

**Volcán · Biblioteca de Recursos Gráficos**

*Organización visual, comunicación corporativa y uso responsable de la información.*
