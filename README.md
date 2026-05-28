# 🎵 Simulador de Microtonos

![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

Un simulador interactivo basado en consola diseñado en **Python** para gestionar, controlar y reproducir secuencias de frecuencias sonoras (microtonos) mediante el hardware de audio de tu equipo. Utiliza la librería nativa de Windows `winsound` para sintetizar los sonidos en tiempo real.

---

## 🚀 Características

* **🎛️ Panel de Control Interactivo:** Navegación simple mediante un menú numérico en la terminal.
* **📊 Gestión de Recursos:** Sistema automatizado que controla un banco limitado de hasta 25 microtonos disponibles.
* **🎼 Secuencia Cíclica Dinámica:** Reproducción de melodías utilizando arreglos de frecuencias (Hz) y duraciones (ms) que se repiten matemáticamente para evitar desbordamientos.
* **🛡️ Entrada Segura (Anti-Crash):** Manejo de excepciones (`try-except`) para evitar que el programa se cierre si introduces texto en lugar de números.

---

## 🛠️ Requisitos del Sistema

* **Sistema Operativo:** Windows 10 / 11 *(Requisito obligatorio: La librería `winsound` es exclusiva de la API de Windows).*
* **Lenguaje:** [Python 3.x](https://www.python.org/) u o superior.
* **Dependencias:** No requiere instalar librerías de terceros (usa módulos de la biblioteca estándar).

---

## 💻 Instalación y Uso

Sigue estos pasos para ejecutar el simulador localmente:

1. **Clona este repositorio:**
   ```bash
   git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
