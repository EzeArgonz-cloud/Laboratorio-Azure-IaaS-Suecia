# Laboratorio-Azure-IaaS-Suecia
Proyecto: Infraestructura Web Segura y Eficiente en Microsoft Azure (IaaS)

# Despliegue de Servidor Web en Azure (Región Suecia)

## 🎯 Objetivo
Demostrar la capacidad de desplegar infraestructura en la nube (IaaS) siguiendo buenas prácticas de seguridad y costos.

## 🛠️ Recursos Creados
* **Virtual Machine:** Ubuntu Server 22.04 LTS (Size: B2ats_v2).
* **Network:** VNet y Subnet configuradas en Sweden Central.
* **Seguridad:** Network Security Group (NSG) filtrado por IP para SSH (Puerto 22) y abierto para HTTP (Puerto 80).
* **Web Server:** Nginx configurado manualmente vía SSH.

## 💰 Optimización de Costos
* Implementación de **Auto-shutdown** diario.
* Configuración de alertas de presupuesto en **Azure Cost Management**.

## 🚀 Cómo lo hice
1. Provisioné la infraestructura mediante el Portal de Azure.
2. Configuré el acceso seguro mediante llaves RSA (.pem).
3. Instalé y personalicé el servidor Nginx mediante comandos de Linux.
