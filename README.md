# Alianza Inmobiliaria

Sitio estático listo para desplegarse en Vercel.

## Despliegue desde GitHub

1. Sube esta carpeta a un repositorio de GitHub.
2. Entra a [vercel.com](https://vercel.com) y pulsa **Add New → Project**.
3. Selecciona el repositorio.
4. Configura el proyecto así:
   - Framework Preset: **Other** (sitio estático)
   - Root Directory: raíz del repositorio
   - Build Command: vacío
   - Output Directory: vacío o `.`
   - Install Command: vacío
5. Pulsa **Deploy**.

La página principal es `index.html` y las demás páginas HTML están en la raíz. `vercel.json` habilita URLs sin la extensión `.html`.

## Verificación local

Puedes abrir `index.html` directamente en el navegador o iniciar un servidor local con Python:

```powershell
python -m http.server 8080
```

Luego abre `http://localhost:8080`.

## Pendiente antes de publicar datos reales

- Conectar los formularios a un servicio real (por ejemplo, Formspree o un CRM).
- Reemplazar los datos de ejemplo de WhatsApp y correo electrónico.
- Revisar y publicar las políticas y términos indicados como pendientes en el sitio.
