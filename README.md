# Application IoT ESP32 - MQTT - Node-RED

> **Projet académique** - Module Technologies IoT  
> ENSA Khouribga | Janvier 2025  
> **Équipe de 4 personnes**

[![ESP32](https://img.shields.io/badge/Hardware-ESP32-blue)](https://www.espressif.com/)
[![MQTT](https://img.shields.io/badge/Protocol-MQTT-green)](https://mqtt.org/)
[![Node-RED](https://img.shields.io/badge/Dashboard-Node--RED-red)](https://nodered.org/)

---

## Vue d'ensemble

Système IoT complet pour **surveillance environnementale** intégrant :
- Acquisition de données via capteurs (température, humidité, pression)
- Transmission temps réel via protocole MQTT
- Visualisation interactive sur dashboard Node-RED

**Contexte :** Projet de groupe réalisé dans le cadre du module Technologies IoT, encadré par Dr. J. Jebrane.

---

## Architecture du Système

![Architecture](docs/architecture.png)

Le système suit une architecture IoT classique en trois couches :

1. **Couche Edge (ESP32)** : Acquisition données capteurs
2. **Couche Communication (MQTT)** : Transmission asynchrone
3. **Couche Application (Node-RED)** : Traitement et visualisation
