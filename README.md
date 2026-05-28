Simulador de Microtonos 🎵
Un simulador interactivo en consola desarrollado en Python que permite gestionar y reproducir frecuencias sonoras utilizando la librería nativa de Windows winsound.

El programa permite experimentar con una secuencia de tonos predefinidos (frecuencias y duraciones), simulando un banco limitado de "microtonos" configurables por el usuario.

🚀 Características
Panel de Control Interactivo: Menú numérico para navegar por las distintas funciones del simulador.

Secuencia Melódica Dinámica: Utiliza listas cíclicas de frecuencias (en Hz) y duraciones (en ms) para generar sonido.

Gestión de Recursos: Sistema de control que limita el uso a un máximo de 25 microtonos.

Control de Errores: Manejo de excepciones (try-except) para evitar caídas si el usuario introduce datos no válidos (letras en lugar de números).

🛠️ Requisitos del Sistema
Sistema Operativo: Windows (imprescindible, ya que la librería winsound es exclusiva de este OS).

Python: Versión 3.x o superior.

Dependencias: Ninguna (utiliza módulos nativos de la biblioteca estándar de Python).

💻 Instalación y Uso
Descarga o clona el archivo con el código fuente (ej. simulador.py).

Abre la consola de comandos (CMD o PowerShell) en la ruta donde guardaste el archivo.

Ejecuta el script con el siguiente comando:

Bash
python actividadMicrotonos.py
