# 👽 0xAlienSec QR Generator

![Version](https://img.shields.io/badge/VERSION-1.0-green?style=for-the-badge) ![Platform](https://img.shields.io/badge/PLATFORM-WEB-blue?style=for-the-badge) ![License](https://img.shields.io/badge/LICENSE-MIT-orange?style=for-the-badge) ![Author](https://img.shields.io/badge/AUTHOR-0XALIENSEC-red?style=for-the-badge)

> **"El conocimiento es libre, el crimen no."**

---

## 📡 Live Demo
Accede a la herramienta online aquí:
### [🔗 https://4l13n-dn.github.io/QR/](https://4l13n-dn.github.io/QR/)

---

## 🏴‍☠️ Descripción
**0xAlienSec QR Generator** es una herramienta web de generación de códigos QR de alta densidad y totalmente personalizable. A diferencia de los generadores comerciales, esta herramienta se ejecuta **100% en el lado del cliente (Client-Side)**, lo que significa que los datos que introduces (claves WiFi, secretos 2FA, direcciones Crypto) **nunca** salen de tu navegador ni se envían a servidores de terceros.

Diseñado con una estética *Cyberpunk/Hacker* y optimizado para operaciones de seguridad, OSINT y uso personal avanzado.

## ⚡ Características Principales

### 🛠️ Payloads Soportados
Genera QRs para múltiples vectores de entrada:
* **Texto / URL:** Con soporte nativo para acortar enlaces (TinyURL).
* **Conectividad:** Credenciales Wi-Fi (Soporte para redes ocultas/Hidden SSID) y SSH.
* **Mensajería:** SMS, WhatsApp (API directa) y Telegram.
* **Seguridad:** 2FA/OTP (Google Authenticator format) y PGP Keys.
* **Criptomonedas:** Direcciones de Bitcoin, Ethereum y Polygon.
* **Otros:** vCard (Contactos), Geolocalización (GPS) y Deep Links de Apps.

### 🧰 Herramientas Integradas (Cyber Chef Lite)
Manipula tu payload antes de generar el código sin salir de la app:
* **Base64** Encoding.
* **URL** Encoding.
* **Hex** Encoding.
* **ROT13** Cipher (Ofuscación básica).

### 🎨 Personalización Avanzada
* **Estilos:** Puntos cuadrados, redondeados, fluidos (líquido) o "Classy".
* **Ojos (Marcadores):** Personalización independiente del marco y el centro de los marcadores de esquina.
* **Colores:** Gradientes lineales personalizados y modo oscuro nativo.
* **Branding:** Inserción de Logos, Imágenes o Caracteres centrales (ej. una letra "A" estilo hacker).
* **Label:** Añade texto de llamada a la acción (ej. "SCAN ME") debajo del QR.

---

## 💻 Instalación Local

Si prefieres ejecutarlo offline en tu propia máquina (air-gapped):

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/4l13n-DN/QR.git](https://github.com/4l13n-DN/QR.git)
    ```
2.  **Entrar al directorio:**
    ```bash
    cd QR
    ```
3.  **Ejecutar:**
    Simplemente abre el archivo `index.html` en tu navegador favorito. No requiere servidor (Node.js/PHP/Python) para funcionar.

---

<div align="center">
  
  **Created by [0xAlienSec](https://github.com/4l13n-DN)**
  
  *Cybersecurity | Red Teaming | Development*
  
</div>
