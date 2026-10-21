# Portada y Tablero M&E - Trata de Personas (Ministerio de Seguridad PBA)

Sitio institucional y visor interactivo para la estrategia de Monitoreo y Evaluación (M&E) del **Programa de fortalecimiento de las capacidades de la policía bonaerense en la lucha contra la trata de personas y delitos conexos**, Ministerio de Seguridad de la Provincia de Buenos Aires.

---

## 📁 Estructura del Proyecto

```text
itera-trata-dashboard/
├── assets/
│   ├── favicon.svg             # Favicon institucional
│   ├── logo_gba.svg            # Isotipo oficial de Gobierno de la Provincia de Buenos Aires
│   └── logo_ministerio.svg     # Logotipo vectorial oficial del Ministerio de Seguridad PBA
├── dashboard.html              # Visor fullscreen con iframe de Looker Studio y botón de retorno
├── index.html                  # Portada institucional (Landing page M&E)
├── netlify.toml                # Configuración de despliegue para Netlify
├── .gitignore                  # Reglas de exclusión de Git
└── README.md                   # Documentación del proyecto
```

---

## 🚀 Despliegue en GitHub y Netlify

### 1. Subir a GitHub
1. Abre una terminal en este directorio y ejecuta (si aún no creaste el repositorio en GitHub):
   ```bash
   git add .
   git commit -m "feat: portada institucional y visor de tablero looker studio"
   git branch -M main
   git remote add origin https://github.com/<TU_USUARIO>/itera-trata-dashboard.git
   git push -u origin main
   ```

### 2. Vincular con Netlify
1. Ingresa a [Netlify](https://app.netlify.com/).
2. Haz clic en **"Add new site"** > **"Import an existing project"**.
3. Selecciona **GitHub** y autoriza el acceso a tu repositorio `itera-trata-dashboard`.
4. En la configuración de build:
   - **Base directory:** (dejar vacío)
   - **Build command:** (dejar vacío)
   - **Publish directory:** `.` (o dejar vacío, ya configurado en `netlify.toml`).
5. Haz clic en **"Deploy itera-trata-dashboard"**. ¡Listo! A partir de ese momento, cualquier cambio que envíes con `git push` se actualizará de forma automática.
