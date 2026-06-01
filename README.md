# tiendamayor-intranet

Portal de documentación interna del equipo · Tienda Mayor · Laboratorio Textil

---

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Portal principal — home de la intranet |
| `manual-bienvenida.html` | Manual de Bienvenida general · Toda la empresa |
| `manual-atencion-al-cliente.html` | Manual de Área · Atención al Cliente |
| `manual-textiles.html` | Guía de Textiles · Área Atención al Cliente |
| `documentos-del-area.html` | Documentos del Área · Atención al Cliente |
| `manual-cobranzas.html` | Manual de Área · Cobranzas |

---

## Estructura de la intranet

```
index.html  ← Home principal
│
├── manual-bienvenida.html            (toda la empresa)
│
└── Área Atención al Cliente
│   ├── manual-atencion-al-cliente.html
│   ├── manual-textiles.html
│   └── documentos-del-area.html
│
├── Área Cobranzas
│   └── manual-cobranzas.html
│
├── Área Producción                   (en preparación)
└── Área Comunicación                 (en preparación)
```

---

## Cómo publicar en GitHub Pages

> ⚠️ **Importante:** GitHub Pages solo funciona gratis con repositorios **públicos**. Si el repositorio es privado, necesitás un plan de pago (GitHub Pro/Team). Para uso interno con URL pública, la opción más sencilla es hacer el repositorio público.

### Paso 1 — Subir los archivos

En la página del repositorio, hacé clic en **"uploading an existing file"** y arrastrá todos los archivos HTML. En *Commit changes*, dejá el mensaje por defecto y confirmá.

### Paso 2 — Activar GitHub Pages

1. Andá a **Settings** (pestaña superior del repositorio)
2. En el menú izquierdo, hacé clic en **Pages**
3. En *Branch*, seleccioná `main` y dejá la carpeta en `/ (root)`
4. Hacé clic en **Save**

### Paso 3 — Obtener la URL

Esperá 1–2 minutos y recargá la página de Settings → Pages. Vas a ver un cartel verde con la URL:

```
https://tuusuario.github.io/tiendamayor-intranet
```

Esa URL la compartís internamente por WhatsApp o la fijás en Notion.

---

## Cómo actualizar un manual

1. Entrá al repositorio en GitHub
2. Hacé clic sobre el archivo que querés reemplazar
3. Arriba a la derecha del archivo, hacé clic en el ícono del lápiz ✏️ o en los tres puntos → *Upload file*
4. Subí la nueva versión con el mismo nombre
5. Los cambios se publican automáticamente en 1–2 minutos

## Agregar un manual nuevo

1. Subí el nuevo archivo HTML al repositorio (mismo proceso que arriba)
2. Editá `index.html` y reemplazá la card "Próximamente" del área correspondiente con los datos del nuevo manual
3. Descargá el `index.html` actualizado y subilo al repositorio

---

*Documentación interna · Tienda Mayor · 2025*
