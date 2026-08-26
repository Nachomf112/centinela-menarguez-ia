# 🛡️ Centinela Menarguez-IA

![Status](https://img.shields.io/badge/status-activo-brightgreen)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-monitor-blue)
![License](https://img.shields.io/badge/license-privado-lightgrey)

Monitor de disponibilidad externo, ligero y sin coste, para la infraestructura de **Menarguez-IA Solutions**. Comprueba cada 5 minutos que los servicios públicos críticos responden correctamente, y envía una alerta instantánea a Telegram en cuanto alguno falla.

## 🎯 Por qué existe

Un monitor alojado dentro de tu propia red (Uptime Kuma, Zabbix, etc.) tiene un punto ciego estructural: si tu conexión a internet se cae, tanto el problema como el aviso de ese problema dependen de la misma conexión rota. **Centinela** resuelve esto ejecutándose fuera de la red de Menarguez-IA, en los servidores de GitHub Actions — así el aviso llega incluso cuando el fallo es de tu propia línea.

## ⚙️ Cómo funciona
