# Skid - Centro de Kinesiología y Rehabilitación Física

Sitio web profesional para **Skid**, un centro integral de salud especializado en múltiples disciplinas terapéuticas.

## 🌐 Características

- ✅ **Diseño Responsivo**: Se adapta perfectamente a desktop, tablet y móvil
- ✅ **Carrusel Automático**: Rotación de servicios destacados cada 5 segundos
- ✅ **Formulario de Comentarios**: Los pacientes pueden dejar reseñas (guardadas en el navegador)
- ✅ **Reserva por WhatsApp**: Botones flotantes y en especialidades para agendar citas
- ✅ **Mapa Integrado**: Ubicación con Google Maps embed
- ✅ **Secciones Completas**:
  - Header sticky con navegación
  - Hero section con CTA
  - Especialidades (Kinesiología, Nutrición, Psicología, Fonoaudiología)
  - Convenios (FONASA, ISAPRE, Seguros, Particular)
  - Formulario de comentarios y vista de reseñas
  - Footer con contacto y redes sociales

## 📂 Estructura del Proyecto

```
nuevo proyecto clinica/
├── index.html          # Archivo principal (HTML + CSS + JS integrados)
├── README.md           # Este archivo
└── .gitignore          # Archivos a ignorar en Git
```

## 🚀 Cómo Publicar en GitHub Pages

### Opción 1: Crear nuevo repositorio en GitHub

1. Ve a [GitHub](https://github.com) y crea un nuevo repositorio
2. Nombre del repositorio: `skid-clinica` (o el que prefieras)
3. **Importante**: Marca la opción **"Initialize this repository with a README"** (opcional, podés sobrescribir)

### Opción 2: Clonar y hacer push desde tu máquina

Abre PowerShell en la carpeta del proyecto y ejecuta:

```powershell
# Navega a la carpeta del proyecto
cd "C:\Users\van_n\OneDrive\Desktop\nuevo proyecto clinica"

# Inicializa git
git init

# Añade todos los archivos
git add .

# Commit inicial
git commit -m "Initial commit - Sitio Skid Clínica"

# Cambia el nombre de la rama a 'main' (GitHub Pages lo requiere)
git branch -M main

# Añade el repositorio remoto (REEMPLAZA con tu usuario y repo)
git remote add origin https://github.com/TU_USUARIO/skid-clinica.git

# Sube el proyecto
git push -u origin main
```

### Opción 3: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Abre **Settings** → **Pages**
3. En **Source**, selecciona **Deploy from a branch**
4. Rama: **main**, Carpeta: **/ (root)**
5. Haz clic en **Save**

Tu sitio estará en: `https://TU_USUARIO.github.io/skid-clinica/`

## 📱 Características Técnicas

- **Lenguaje**: HTML5 + CSS3 + Vanilla JavaScript
- **Sin dependencias externas**: Todo integrado en un único archivo
- **Imágenes**: Almacenadas en CDN (Unsplash, Icons8, Wikimedia)
- **Almacenamiento**: Comentarios guardados en localStorage del navegador

## 🎨 Personalización

Edita directamente en `index.html`:

- **Línea 4**: Cambia el título de la página
- **Línea ~787**: Actualiza números de WhatsApp (reemplaza `5491234567890`)
- **Línea ~988-1026**: Modifica especialistas, descripciones y números
- **Línea ~1037-1055**: Datos de contacto (teléfono, email, dirección)
- **Línea ~850-870**: Textos del carrusel de servicios

## 📞 WhatsApp Integration

El botón "Escríbenos" y los botones de reserva abren WhatsApp con mensajes preformateados:
- URL base: `https://wa.me/NUMERO?text=MENSAJE`
- Reemplaza `NUMERO` con tu número de WhatsApp (formato internacional, ej: 5491234567890)

## 🌟 Compatibilidad

- ✅ Chrome, Firefox, Safari, Edge (últimas 2 versiones)
- ✅ iOS y Android
- ✅ Responsive en todos los tamaños

## 📝 Licencia

Este proyecto es para uso privado de Skid Clínica.

## 📧 Contacto

Para cambios o mejoras, contacta al equipo de desarrollo.

---

**Versión**: 1.0  
**Última actualización**: Diciembre 2025
