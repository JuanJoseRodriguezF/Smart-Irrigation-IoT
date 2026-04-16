# Smart Irrigation System con ESP32 y Bluetooth

## Visión del Proyecto

Este proyecto implementa un sistema de riego inteligente basado en IoT que permite monitorear variables ambientales en tiempo real y automatizar el riego de plantas mediante el uso de sensores y un microcontrolador ESP32.

### Problema
- Riego ineficiente en huertos pequeños
- Desperdicio de agua
- Falta de monitoreo continuo

### Usuarios Objetivo
- Personas con huertos caseros
- Agricultores urbanos
- Estudiantes y proyectos educativos

---

## Arquitectura del Sistema

### Diagrama de bloques

<img width="826" height="164" alt="sistemaProyecto" src="https://github.com/user-attachments/assets/cfd86d9f-0130-480b-9015-96b7c2c8ab8a" />


### Componentes

- ESP32 (controlador principal)
- Sensor de humedad del suelo
- Sensor DHT22 (temperatura y humedad)
- LDR (sensor de luz)
- Sensor de nivel de agua
- Bomba de agua (con relé)

---

## Restricciones

### Hardware
- RAM ESP32: ~520 KB
- Alimentación: 5V (posible uso de batería)
- Alcance Bluetooth: ~10 metros

### Económicas
- Presupuesto estimado: $80.000 - $150.000 COP

### Técnicas
- Precisión limitada de sensores
- Posibles interferencias en Bluetooth
- Consumo energético del sistema

---

## Spike Arquitectónico

### Objetivo
Validar la comunicación entre el ESP32 y una aplicación móvil mediante Bluetooth (BLE).

### Resultado
- Conexión BLE estable lograda
- Envío de datos en tiempo real
- Latencia menor a 1 segundo

Ver reporte completo en: `docs/spike-report.md`

---

## MVP (Minimum Viable Product)

### Must Have
- Lectura de sensores
- Envío de datos vía Bluetooth
- Visualización en aplicación móvil
- Activación automática de riego

### Nice to Have
- Historial de datos
- Alertas inteligentes
- Recomendaciones de riego
- Dashboard avanzado

---

## Cronograma de Desarrollo

### 🔹 Release 1 (Semanas 1-2)
- Validación técnica (Spike)
- Configuración de sensores
- Definición de arquitectura

### 🔹 Release 2 (Semanas 3-4)
- Integración de sensores
- Comunicación Bluetooth
- App básica funcional

### 🔹 Release 3 (Semanas 5-6)
- Automatización del riego
- Lógica de decisión
- Alertas

### 🔹 Release 4 (Semanas 7-8)
- Pruebas finales
- Corrección de errores
- Documentación y presentación

---

## Tecnologías

- ESP32
- Arduino IDE
- Bluetooth Low Energy (BLE)
- App móvil (MIT App Inventor / Flutter / Android)

---

## Equipo

- Juan José Rpdríguez
- Wilson Santiago Bonilla
- María Fernanda Tamayo

---

## Estado del Proyecto

En desarrollo - Release 1
