# Diagnóstico Integral – Red Sanitaria Hospital Briceño

## Estructura para GitHub

- `index.html` → página web principal.
- `fotos/` → fotografías separadas por nivel y evidencias de los puntos de inspección.
- `mapas/` → mapa aéreo, Localización Cajas de Inspección Sanitaria y **Red de Drenaje Sanitario** (antes “Planta Hidráulica”).
- `documentos/` → documentos técnicos de soporte.
- `datos/` → archivos de datos de trabajo.

## Cómo actualizar fotos
1. Entra a la carpeta del nivel correspondiente.
2. Sube la nueva foto.
3. Para que aparezca automáticamente en la galería, agrega su referencia en `const PHOTOS` dentro de `index.html` (manteniendo `floor`, `floorName`, `label` y `src`).

## Cómo actualizar mapas y planos
Los archivos se encuentran en `mapas/`. Si reemplazas un archivo manteniendo el mismo nombre, los botones de la página seguirán funcionando.

## Publicación con GitHub Pages
Puedes usar este mismo repositorio para publicar `index.html`. Si luego conectas el repositorio a Netlify, la misma estructura también funciona y se actualiza automáticamente cuando haces `git push`.

## Nota
El repositorio contiene información técnica del hospital. Se recomienda mantenerlo **privado** si el contenido no está destinado a publicación abierta.
