# SIE — Soluciones Informáticas Empresariales

## Estructura del proyecto

```
sie-web/
├── index.html        ← Página pública
├── admin.html        ← Panel de administración
├── SIE_Logo2.png     ← Logo (copiar aquí)
├── netlify.toml      ← Configuración de Netlify
└── README.md
```

## Setup en VS Code

1. Crea carpeta `sie-web` en tu equipo
2. Copia todos los archivos aquí
3. Abre la carpeta en VS Code

## Subir a GitHub

```bash
git init
git add .
git commit -m "SIE Landing v1.0"
git remote add origin https://github.com/TU_USUARIO/sie-web.git
git push -u origin main
```

## Conectar Netlify

1. Entra a netlify.com
2. "Add new site" → "Import an existing project"
3. Conecta tu repo GitHub sie-web
4. Deploy — automático en cada git push

## Panel Admin

URL: `https://tu-sitio.netlify.app/admin`

- **Cubano** (cubano@sie.com) → gestiona Software
- **Socio** (phdez@sie.com) → gestiona Hardware

## Supabase

- URL: https://buentywjbnlbmplmwprx.supabase.co
- Las fotos se guardan en Storage → fotos-productos
- Los productos en Table → productos
