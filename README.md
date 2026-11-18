# LabEnergy: El Cargador Fantasma
**Laboratorio Virtual / Laboratorio en el Bolsillo – Ingeniería Civil Industrial**

Web App interactiva para medir, visualizar y traducir a pesos chilenos (CLP) el consumo eléctrico en modo espera ("consumo vampiro") de dispositivos cotidianos.

## Enlace a la App Activa (MVP)
👉 [Abrir LabEnergy en vivo](https://consumo-fantasma-app.netlify.app/)

## Equipo y Roles
* **Eduardo:** Product Owner / Líder de Proyecto
* **Mayra Oyarzún:** Responsable Científica
* **Nicolás Díaz:** Responsable de Hardware e Instrumentación
* **Javier Arancibia:** Responsable de Software y Motor de Datos
* **Kevin Chaux:** Responsable UX/UI
* **Rafaella Larenas:** Responsable Pedagógica y Documentación

## Stack Tecnológico
* **Hardware:** Microcontrolador ESP32 + Sensor SCT-013 / módulo PZEM-004T (validado contra medidor comercial Kill A Watt).
* **Software & Datos:** HTML5, Tailwind CSS, JavaScript (ES6+) y Chart.js.
* **Despliegue:** Netlify (Web App) y GitHub (repositorio y bitácora).

## Instrucciones de Uso
1. Abrir el enlace de la Web App desde cualquier navegador móvil o de escritorio.
2. En **Medir Vivo**, seleccionar un dispositivo en espera para visualizar potencia (W), corriente (A) y costo proyectado, o probar la simulación de desenchufe.
3. En **Mi Depto**, configurar el inventario de aparatos y horas diarias en standby para calcular el gasto mensual y anual en CLP.
4. En **Validación**, contrastar las lecturas del sensor frente al medidor comercial.
