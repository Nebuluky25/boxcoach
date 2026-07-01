# BOX COACH IA — Elite Training Generator

Generador de sesiones de CrossFit con IA real integrada.

## 📋 Archivos necesarios

```
boxapp/
├── index.html           (App principal)
├── manifest.json        (Configuración PWA)
├── sw.js               (Service Worker)
├── icon-192.svg        (Icono pequeño)
├── icon-512.svg        (Icono grande)
├── vercel.json         (Config Vercel)
├── .env.example        (Plantilla de variables)
└── api/
    └── generate-session.js  (Backend seguro)
```

## 🚀 Instalación en Vercel (GRATUITO - 5 minutos)

### PASO 1: Preparar archivos en GitHub

1. Ve a **github.com** → Sign in
2. Crea un repositorio nuevo llamado `boxcoach`
3. Sube TODOS estos archivos:
   - index.html
   - manifest.json
   - sw.js
   - icon-192.svg
   - icon-512.svg
   - vercel.json
   - .env.example
   - api/generate-session.js

### PASO 2: Conectar a Vercel

1. Abre **vercel.com** → Sign up con GitHub
2. Click **Import Project**
3. Selecciona tu repositorio `boxcoach`
4. Click **Deploy**

### PASO 3: Añadir API Key

1. En el dashboard de Vercel, ve a **Settings** → **Environment Variables**
2. Añade:
   - Name: `ANTHROPIC_API_KEY`
   - Value: `tu-clave-api-de-anthropic`
3. Click **Save**
4. **Redeploy**: Click el botón de redeploy

### PASO 4: Tu URL en vivo

Vercel te da una URL tipo: `https://boxcoach.vercel.app`

Abre en Safari y listo.

## 📱 Instalar en iPhone como APP

1. Abre la URL en **Safari**
2. Pulsa el botón **Compartir** ↑
3. Pulsa **"Añadir a pantalla de inicio"**
4. Nombre: **BOX COACH**
5. Click **Añadir**

✅ Aparece como app nativa en tu pantalla de inicio.

## 🔑 ¿Dónde conseguir la API Key?

1. Ve a **console.anthropic.com**
2. Inicia sesión o crea cuenta (gratuita)
3. **API Keys** → **Create Key**
4. Copia la clave
5. Pégala en las Environment Variables de Vercel

## ✨ Características

✓ IA Claude Sonnet integrada
✓ Warm-ups únicos cada día
✓ Strength con cargas precisas
✓ WOD formatos variados
✓ 14 participantes máximo
✓ Modo verano optimizado
✓ Escalados completos
✓ Guardado automático

## 🛠️ Problemas?

- **Error de conexión**: Verifica que la API Key esté en Vercel
- **App no carga**: Limpia caché de Safari (Settings → Safari → Clear History)
- **No genera sesiones**: Recarga la página

---

**BOX COACH IA** — Entrena con inteligencia. Nunca repite. Siempre evoluciona. ⚡
