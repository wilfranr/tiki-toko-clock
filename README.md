# Reloj Digital - PWA

Una aplicación de reloj digital moderna y elegante diseñada específicamente para dispositivos móviles como Progressive Web App (PWA).

## ✨ Características

### 🎨 Diseño Moderno
- **Fondo negro** elegante y moderno
- **Sistema de configuración de colores** personalizable
- **Efectos visuales** con brillo y animaciones suaves
- **Diseño responsive** optimizado para móviles
- **Interfaz minimalista** con tipografía moderna

### ⚙️ Configuración de Colores
- **Color del reloj**: Personaliza el color de los números del reloj
- **Color de la fecha**: Configura el color del texto de la fecha
- **Color del clima**: Personaliza el color de la temperatura
- **Color de acento**: Configura el color de elementos adicionales
- **Persistencia**: Los colores se guardan automáticamente en el navegador

### 📱 Funcionalidades PWA
- **Instalable** como aplicación nativa
- **Funciona offline** con Service Worker
- **Iconos adaptativos** para diferentes tamaños
- **Splash screen** personalizado
- **Orientación optimizada** para móviles

### 🌤️ Información en Tiempo Real
- **Reloj digital** con formato 24 horas
- **Fecha completa** en español
- **Información del clima** basada en ubicación GPS
- **Hora local** y zona horaria
- **Actualización automática** cada segundo

## 🚀 Instalación

1. **Clona el repositorio**:
   ```bash
   git clone [url-del-repositorio]
   cd clock
   ```

2. **Abre la aplicación**:
   - Abre `index.html` en tu navegador
   - O sirve los archivos con un servidor local

3. **Instala como PWA**:
   - En Chrome/Edge: Busca el icono de instalación en la barra de direcciones
   - En Safari: Usa "Agregar a pantalla de inicio"
   - En Android: Usa "Agregar a pantalla de inicio"

## 🎯 Uso

### Configuración de Colores
1. Toca el icono de configuración (⚙️) en la esquina superior derecha
2. Selecciona los colores que desees para cada elemento
3. Toca "Guardar" para aplicar los cambios
4. Los colores se guardarán automáticamente para futuras sesiones

### Funcionalidades
- **Reloj**: Se actualiza automáticamente cada segundo
- **Clima**: Obtiene datos basados en tu ubicación GPS
- **Información adicional**: Muestra hora local y zona horaria

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con variables CSS
- **JavaScript ES6+** - Funcionalidad interactiva
- **Tailwind CSS** - Framework de utilidades
- **Google Fonts** - Tipografías Orbitron e Inter
- **Open-Meteo API** - Datos del clima
- **Service Worker** - Funcionalidad offline

## 📱 Compatibilidad

- ✅ Chrome/Chromium (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Navegadores móviles

## 🎨 Personalización

La aplicación utiliza variables CSS para la personalización de colores:

```css
:root {
  --clock-color: #00ff88;    /* Color del reloj */
  --date-color: #ffffff;     /* Color de la fecha */
  --weather-color: #00d4ff;  /* Color del clima */
  --accent-color: #ff6b35;   /* Color de acento */
}
```

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o pull request para sugerir mejoras.

---

**Desarrollado con ❤️ para una experiencia de reloj digital moderna y personalizable.**
