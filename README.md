# 🌬️ Monitor de Levante en Cádiz

Aplicación web HTML que muestra en tiempo real si hay viento de levante en Cádiz, con pronóstico para 7 días. Ideal para navegantes, surfistas y amantes del clima.

## 🚀 Características

- ✅ **Detección automática** de posible levante (Vientos E/NE > SE/ENE de más de 20 km/h)
- 📅 Pronóstico semanal con porcentajes de probabilidad
- 📱 Diseño responsive (funciona en móviles y desktop)
- 🕒 Día actual subrayado
- 🔄 Actualización manual con un botón
- 🌍 Datos en tiempo real de Open-Meteo API

## 🛠️ Tecnologías

- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (Fetch API)
- [Open-Meteo API](https://open-meteo.com/)

## 📸 Captura de pantalla

![Captura de pantalla](https://github.com/DavidLora2000/web-levante-cadiz/blob/main/captura-ejemplo-1.png)

## 📦 Instalación

1. Clona el repositorio o descarga `index.html`
2. Ábrelo directamente en cualquier navegador (Chrome, Firefox, Edge)
3. ¡Listo! No requiere servidor ni dependencias

## 🧑‍💻 Personalización

Edita estos parámetros en el código si necesitas ajustes:

```javascript
// Coordenadas (Cádiz por defecto)
const latitude = 36.5298;
const longitude = -6.2926;

// Umbral de velocidad del viento (km/h)
const windThreshold = 20;
