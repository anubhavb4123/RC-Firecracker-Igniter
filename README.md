# RC Firecracker Igniter (Gen 8)

This project is an **RC-based wireless firecracker igniter** that uses a relay mechanism and a nichrome wire for ignition.
The system is controlled using an RC transmitter and receiver pair to remotely activate the igniter circuit.

## 🔧 Components Used

- RC Transmitter and Receiver Pair (e.g., 433 MHz RF module)
- Relay Module
- Nichrome Wire (For heating)
- LEDs for indication
- Transistors (to drive relay)
- Resistors (220Ω, 470Ω)
- Power Source (e.g., 5V battery or adapter)
- Push Buttons (for transmission trigger)

## ⚙️ How It Works

1. The **RC transmitter** sends a signal when a button is pressed.
2. The **RC receiver** receives the signal and activates a transistor that energizes the **relay**.
3. The relay closes the normally open (NO) contact, allowing current to flow through the **nichrome wire**.
4. The nichrome wire heats up and ignites the firecracker.
5. LEDs indicate system status: transmission, reception, and ignition.

## ⚠️ Safety Precautions

- Always test with dummy loads before using with real firecrackers.
- Use in a controlled outdoor environment.
- Ensure safe distance while triggering.
- Wear protective gear and follow local regulations.

## 💡 Author

Made with ❤️ by [Anubhav Bajpai]
