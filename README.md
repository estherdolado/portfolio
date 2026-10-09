# Esther Dolado · Fotografía de maternidad

Web de portfolio de **Esther Dolado**, fotógrafa documental de maternidad y familia en Madrid.

🔗 **Web publicada:** https://estherdolado.github.io/esther-dolado-portfolio/
📸 **Instagram:** [@estherdoladophoto](https://instagram.com/estherdoladophoto)

---

## Qué incluye

- Banner de portada a todo el ancho
- Presentación de la fotografía documental de maternidad y familia
- Portfolio por tipo de sesión (Embarazo, Postparto y recién nacido, Familia) con visor de fotos ampliadas
- Apartado "Cómo trabajo", "Esta soy yo" y sesiones
- Contacto por Instagram y email
- Diseño con fondo blanco, adaptado a móvil y ordenador

## Estructura del proyecto

```
├── index.html      → toda la web (texto, diseño y funcionamiento)
├── README.md       → este archivo
└── fotos/          → imágenes de la web
    ├── portada.jpg       (banner superior)
    ├── esther.jpg        (foto de "Esta soy yo")
    ├── embarazo-1.jpg … embarazo-6.jpg
    ├── postparto-1.jpg … postparto-6.jpg
    └── familia-1.jpg … familia-6.jpg
```

## Cómo cambiar las fotos

1. Prepara las imágenes en formato **JPG**, con el nombre exacto de la lista anterior (minúsculas, sin espacios ni acentos).
2. Comprímelas antes de subirlas: unos **300-600 KB** cada una, y la portada hasta unos 700 KB, para que la web cargue rápido.
3. En el repositorio, entra en la carpeta `fotos` y pulsa **Add file → Upload files**. Si subes una con el mismo nombre, sustituye a la anterior.
4. Pulsa **Commit changes**.

Si una foto no existe, esa casilla se muestra vacía con el nombre del archivo que falta.

### Cambiar el número de fotos por categoría

En `index.html`, busca el bloque `CATEGORIES` (cerca del final del archivo) y cambia el número de `count`:

```js
{ id:'embarazo', label:'Embarazo', count:6 },
```

## Cómo cambiar los textos y datos de contacto

1. Abre `index.html` en GitHub y pulsa el icono del **lápiz** (Edit).
2. Usa la búsqueda del navegador (Cmd+F) para encontrar el texto que quieres cambiar.
3. Pulsa **Commit changes** para guardar.

Cosas que conviene revisar:

- **Email:** busca `TUEMAIL@ejemplo.com` y cámbialo por tu correo real.
- **Instagram:** el enlace es `https://instagram.com/estherdoladophoto`.

## Cómo se publica

La web usa **GitHub Pages**. Cada vez que guardas un cambio (*Commit changes*) en la rama `main`, la web se actualiza sola en 1-2 minutos.

Si no ves el cambio, recarga forzando la caché con **Cmd+Shift+R** (Mac) o **Ctrl+Shift+R** (Windows).

Ajuste necesario en el repositorio: **Settings → Pages → Source:** rama `main`, carpeta `/ (root)`.

## Tecnología

HTML, CSS y JavaScript en un solo archivo, sin instalaciones ni dependencias. Tipografías de Google Fonts: Cormorant Garamond y Work Sans.

---

© Esther Dolado. Todas las fotografías de esta web son propiedad de la autora y no pueden usarse sin su permiso.
