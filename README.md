🛰️ SmartAgro v1.0
Sistema Inteligente de Predicción Climática para la Optimización Agrícola Regional
Este proyecto forma parte del avance del 30% de la investigación sobre el uso de tecnologías de información para la protección de cultivos y predicción de rendimiento en la región de Sincelejo, Sucre.

📝 Descripción
El sistema es un dashboard interactivo que consume datos en tiempo real de la API Open-Meteo. Utiliza modelos de predicción global para analizar variables críticas y emitir alertas tempranas de riego o estrés térmico.

🚀 Características Técnicas
Consumo de API REST: Conexión asíncrona con Open-Meteo (Sin latencia).

Variables Monitoreadas: * Temperatura del aire (°C).

Humedad del suelo (0-10cm).

Evapotranspiración (FAO ET0).

Punto de Rocío (Dew Point).

Visualización de Datos: Gráficas dinámicas mediante Chart.js con doble eje Y para correlación de variables.

Algoritmo de Predicción: Lógica basada en umbrales de seguridad agrícola y tendencias de las últimas 48 horas.

🛠️ Tecnologías Utilizadas
Frontend: HTML5, CSS3 (Bootstrap 5).

Lógica: JavaScript (Vanilla JS / ES6).

Gráficos: Chart.js.

Datos: Open-Meteo API (Modelos GFS/ECMWF).

📊 Metodología de Predicción
Para este avance del 30%, el sistema evalúa la Tasa de Evaporación Proyectada. Si la pérdida de agua estimada para las próximas 24h supera los 4.5mm y la humedad actual es inferior al 30%, el sistema dispara una alerta de prioridad alta.
