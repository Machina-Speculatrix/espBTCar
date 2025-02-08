**Bluetooth Controlled Car**

This project is a Bluetooth-controlled car using an ESP32 NodeMCU. The car can be operated via Bluetooth commands sent from a mobile application.

**Features**
- Bluetooth control using ESP32
- Adjustable speed settings
- Various movement controls (forward, backward, left, right, etc.)

**Components Required**
- ESP32 NodeMCU (ESP-WROOM-32S)
- L298 Mini Motor Driver
- 2 DC Motors
- Bluetooth module (integrated in ESP32)
- Power source (Li-Ion battery or adapter)

**Pin Configuration**

| Function  | ESP32 Pin |
|-----------|----------|
| Right Motor Forward | GPIO 18 |
| Right Motor Backward | GPIO 19 |
| Left Motor Forward | GPIO 16 |
| Left Motor Backward | GPIO 17 |

**Installation & Setup
**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bluetooth-car.git
   cd bluetooth-car
   ```
2. Install Arduino IDE and ESP32 Board Support Package.
3. Install required libraries in Arduino IDE:
   - `BluetoothSerial`
4. Open `bluetooth_Car.ino` in Arduino IDE.
5. Select the correct ESP32 board and COM port.
6. Upload the code to ESP32.

**Bluetooth Control**

- Connect to the car via a Bluetooth terminal app.
- Send commands:
  - `F` - Move Forward
  - `B` - Move Backward
  - `L` - Turn Left
  - `R` - Turn Right
  - `S` - Stop
  - `I` - Forward Right
  - `J` - Backward Right
  - `G` - Forward Left
  - `H` - Backward Left

**Troubleshooting
**
- Ensure ESP32 is powered correctly.
- Check the Bluetooth connection.
- Verify correct pin assignments in code.

**License**

This project is open-source and available under the MIT License.

