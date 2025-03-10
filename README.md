# Connecting-to-wifi-with-Wemos-D1-R2




############# NOTE : WEMOS WIFI MODULE IS ONLY COMPATABLE WITH 2.4G WIFI #############


# Wemos D1 R2 Wi-Fi Connection

This repository demonstrates how to connect your Wemos D1 R2 microcontroller to a Wi-Fi network using the `ESP8266WiFi` library.

## Hardware Requirements
- Wemos D1 R2 (ESP8266-based board)
- USB cable for programming
- Wi-Fi network

## Software Requirements
- Arduino IDE
- ESP8266 Board Package (Install via Arduino Board Manager)

## Installation
1. Install the **ESP8266 Board Package** in Arduino IDE:
   - Go to **File** → **Preferences**
   - In the "Additional Board Manager URLs" field, add the following URL:
     ```
     http://arduino.esp8266.com/stable/package_esp8266com_index.json
     ```
   - Open **Tools** → **Board** → **Board Manager...**
   - Search for **ESP8266** and install the latest version.

2. Select your board:
   - Go to **Tools** → **Board** → Select **"Wemos D1 R2 & mini"**

3. Connect your Wemos D1 R2 via USB.

4. Upload the code by clicking the **Upload** button.

## Usage
1. Update the `ssid` and `password` variables with your Wi-Fi credentials.
2. Open the **Serial Monitor** (set baud rate to **115200**) to view connection status.
3. Once connected, your Wemos D1 R2 will display its assigned IP address.

## Troubleshooting
- Ensure your Wi-Fi credentials are correct.
- If the connection fails, try pressing the **RST** button on the board.
- Verify that your Wi-Fi frequency is 2.4GHz, as ESP8266 does not support 5GHz.

## License
This project is open-source and available under the MIT License.
