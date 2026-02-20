📁 UnnamedPortal

    A minimalist Captive Portal & Credential Research Tool for ESP32.

UnnamedPortal is a lightweight, stealthy implementation of a Captive Portal using an ESP32 and an SH1106 OLED display. It creates a localized Wi-Fi network that serves a pixel-perfect Google login clone to connected clients, capturing inputs for educational analysis and security auditing.
🚀 Features

    Google Auth Clone: A high-fidelity, mobile-responsive Material Design login page.

    DNS Hijacking: Automatically redirects all connected traffic to the portal.

    OLED HUD: Real-time status monitoring (IP, Admin credentials, and Capture count).

    Web Manager: A password-protected /admin dashboard to view and clear logs.

    Minimalist Code: Highly optimized for the ESP32’s RAM and Flash memory.

🛠️ Hardware Requirements

    Microcontroller: ESP32 (DevKit V1 or similar).

    Display: OLED 128x64 (SH1106 via I2C).

    Software: Arduino IDE with WiFi, DNSServer, WebServer, and U8g2 libraries.

📡 Quick Start

    Flash the Code: Upload the provided .ino file to your ESP32.

    Connect: Look for a Wi-Fi network named "unnamed portal".

    Capture: Once a client "logs in," the OLED will display STATUS: DATA CAPTURED!.

    Manage: Access the dashboard to view results:

        URL: http://192.168.4.1/admin

        User: unnamed

        Pass: portal

⚖️ Legal Disclaimer

This project is created for educational and ethical security testing purposes only. Using this tool against networks or users without explicit permission is illegal. The author is not responsible for any misuse or damage caused by this program.
