# Portal de Egresados INFORTEC

Portal web oficial para egresados del Instituto de Formación Técnica INFORTEC.

## 🚀 Demo en Vivo

Visita el portal: [https://desarrolloinfortecr.github.io/portal-egresados](https://desarrolloinfortecr.github.io/portal-egresados)

## 📋 Credenciales de Prueba

### Egresado
- **Email:** egresado@infortec.edu.co
- **Contraseña:** 123456

### Administrador
- **Email:** admin@infortec.edu.co
- **Contraseña:** admin123

## ✨ Características

### Para Egresados
- ✅ Inicio de sesión seguro
- ✅ Perfil personalizable
- ✅ Visualización de eventos
- ✅ Dashboard intuitivo
- ✅ Responsive design

### Para Administradores
- ✅ Panel de control con estadísticas
- ✅ Vista de administración
- ✅ Gestión de contenido
- ✅ Acceso a funciones avanzadas

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con Tailwind CSS
- **JavaScript ES6+** - Funcionalidad interactiva
- **Font Awesome** - Iconografía
- **LocalStorage** - Persistencia de datos

## 📱 Compatibilidad

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Dispositivos móviles

## 🚀 Instalación Local

1. **Clonar el repositorio:**
\`\`\`bash
git clone https://github.com/DesarrolloInfortecr/portal-egresados.git
cd portal-egresados
\`\`\`

2. **Abrir en navegador:**
\`\`\`bash
# Opción 1: Abrir directamente
open index.html

# Opción 2: Servidor local con Python
python -m http.server 8000

# Opción 3: Servidor local con Node.js
npx serve .
\`\`\`

3. **Acceder al portal:**
\`\`\`
http://localhost:8000
\`\`\`

## 📂 Estructura del Proyecto

\`\`\`
portal-egresados/
├── index.html          # Página principal con toda la aplicación
├── README.md           # Documentación del proyecto
└── .github/            # Configuración de GitHub Actions
    └── workflows/
        └── deploy.yml  # Deploy automático
\`\`\`

## 🔧 Configuración

### Personalizar Datos
Edita las variables en `index.html` dentro del objeto `CONFIG`:

\`\`\`javascript
const CONFIG = {
    app: {
        name: 'Portal de Egresados INFORTEC',
        version: '1.0.0'
    },
    users: [
        // Agregar más usuarios aquí
    ],
    events: [
        // Agregar más eventos aquí
    ]
};
\`\`\`

### Cambiar Estilos
Modifica las clases de Tailwind CSS o agrega CSS personalizado en la sección `<style>`.

## 🌐 Despliegue

### GitHub Pages (Automático)
1. Push al repositorio
2. Ir a Settings > Pages
3. Seleccionar branch `main`
4. El sitio estará disponible en: `https://desarrolloinfortecr.github.io/portal-egresados`

### Netlify
1. Conectar repositorio GitHub
2. Deploy automático
3. URL personalizada disponible

### Vercel
1. Importar proyecto desde GitHub
2. Deploy automático
3. Dominio personalizado incluido

## 🔐 Seguridad

- Validación de datos en frontend
- Sanitización básica de inputs
- Sesiones con expiración automática
- Protección contra XSS básica

> **Nota:** Para producción, implementar autenticación del lado del servidor.

## 📊 Funcionalidades Futuras

### Versión 1.1
- [ ] Sistema de notificaciones push
- [ ] Registro de nuevos usuarios
- [ ] Recuperación de contraseña
- [ ] Integración con API backend

### Versión 1.2
- [ ] Chat en tiempo real
- [ ] Sistema de pagos
- [ ] Bolsa de empleo
- [ ] Certificaciones digitales

### Versión 2.0
- [ ] App móvil (PWA)
- [ ] Inteligencia artificial
- [ ] Analytics avanzados
- [ ] API pública

## 🤝 Contribución

1. Fork el proyecto
2. Crear branch para feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. Push al branch (`git push origin feature/nueva-funcionalidad`)
5. Crear Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más detalles.

## 📞 Soporte

- **Email:** soporte@infortecr.edu.co
- **Teléfono:** +57 1 234 5678
- **Dirección:** Carrera 15 #93-47, Bogotá, Colombia

## 🏆 Créditos

Desarrollado con ❤️ para la comunidad de egresados INFORTEC.

### Equipo de Desarrollo
- **Desarrollo Frontend:** Equipo INFORTEC
- **Diseño UX/UI:** Equipo INFORTEC
- **Testing:** Comunidad de Egresados

---

**¿Encontraste un bug o tienes una sugerencia?** 
[Crear un issue](https://github.com/DesarrolloInfortecr/portal-egresados/issues/new)

**¿Quieres contribuir?** 
[Ver guía de contribución](CONTRIBUTING.md)
