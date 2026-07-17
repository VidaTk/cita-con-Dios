# Cita con Dios

App espiritual interactiva para práctica de protocolo de oración y transformación personal.

## Características

- ✨ Protocolo de 7 sesiones (60 minutos)
- 👥 Personalización por género (Hombre/Mujer)
- 📱 Diseño responsive para móviles
- 💾 Guarda registro de citas completadas
- 🙏 Oraciones expandibles por sesión
- 📤 Compartir progreso por WhatsApp
- 🎨 Diseño minimalista (crema, dorado, azul oscuro)

## Estructura

```
cita-con-dios/
├── index.html      # App completa (HTML + CSS + JS)
├── README.md       # Este archivo
└── .gitignore
```

## Instalación Local

```bash
# Clonar o descargar
git clone https://github.com/tu-usuario/cita-con-dios.git
cd cita-con-dios

# Abrir en navegador
# Simplemente abre index.html en tu navegador
```

## Despliegue en Vercel

### Opción 1: Desde GitHub + Vercel (Recomendado)

1. **Crea repositorio en GitHub**
   - Ve a https://github.com/new
   - Nombre: `cita-con-dios`
   - Sube los archivos

2. **Conecta con Vercel**
   - Ve a https://vercel.com/import
   - Selecciona el repo `cita-con-dios`
   - Vercel detecta automáticamente que es HTML estático
   - Click en "Deploy"

3. **Configura dominio personalizado** (opcional)
   - En Vercel → Proyecto → Settings → Domains
   - Agrega tu dominio (ej: `citacondios.vidabiz.app`)
   - En GoDaddy, apunta el CNAME a `cname.vercel-dns.com`

### Opción 2: Despliegue Manual desde CLI

```bash
# Instala Vercel CLI
npm install -g vercel

# En la carpeta del proyecto
vercel

# Sigue las instrucciones en pantalla
```

## Uso

1. **Abre la app** en navegador
2. **Selecciona género** (Hombre/Mujer)
3. **Lee la frase** motivacional
4. **Haz clic en "Comenzar la sesión 1"**
5. **Sigue cada sesión** (leer procesos, oraciones opcionales)
6. **Haz clic en "Avanzar"** para siguiente sesión
7. **En la última**, haz clic "Completar"
8. **Comparte tu progreso** por WhatsApp (opcional)

## Datos y Privacidad

- ✅ Los datos se guardan **solo en tu dispositivo** (localStorage)
- ✅ No hay servidor, no se envían datos a internet
- ✅ Puedes compartir progreso manualmente por WhatsApp

## Personalización

Edita `index.html` para cambiar:

- **Colores**: Variables CSS en `:root`
  ```css
  --cream: #FFF8F3
  --gold: #D4AF37
  --dark-blue: #003B5C
  ```
- **Textos**: En el array `sessions` (línea ~150 en el `<script>`)
- **Oraciones**: Modifica directamente en el array

## Soporte

Para reportar bugs o sugerencias, abre un issue en GitHub.

---

**Creado con ❤️ por VidaBiz**
