# 💼 Sistema Financiero Todo-en-Uno para Freelancers (Secure & Hardened)

Una aplicación web de interfaz única (*Single-File Architecture*) diseñada específicamente para profesionales independientes en Latinoamérica y el ámbito internacional. Esta herramienta permite gestionar todo el ciclo financiero de un proyecto de forma local, segura y privada.

## 🚀 ¡Pruébala en vivo ya mismo!
👉 **[Haz clic aquí para abrir la aplicación en producción](https://github.io)**

## 🌟 Características Principales
*   **🧮 Calculadora de Tarifa Inteligente:** Deduce tu tarifa por hora basándose en salario deseado, gastos fijos y horas semanales reales (bajo estándar de 4.33 semanas al mes).
*   **📋 Facturación Dinámica Multi-servicio:** Desglosa múltiples servicios en formato de tabla interactiva, calculando subtotales, IVA configurable y totales al instante.
*   **🔒 Blindaje de Seguridad (SRI + XSS):** Bloqueo automático de inyección de código de terceros mediante validación criptográfica SHA-384 en librerías fijas e inmutables. Sanitización estricta del DOM.
*   **💾 Inmunidad a Pérdida de Datos:** Integración con `localStorage` para el auto-guardado en tiempo real de cada pulsación de tecla.
*   **⚖️ Cumplimiento Legal LATAM:** El sistema opera bajo el marco internacional de **Factura Proforma / Payment Request** para evitar conflictos tributarios con entes locales (SAT, DIAN, AFIP, etc.).

## 🛠️ Tecnologías Utilizadas
*   HTML5 Semántico y Válido.
*   Tailwind CSS v4 (Distribución estática).
*   JavaScript Moderno Vanilla (Bajo directiva estricta `'use strict'`).
*   jsPDF & jsPDF-AutoTable (Descarga nativa de PDF en milisegundos).
