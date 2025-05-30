# Auto Water Pump Shutdown using ESP32

a smart system to **automatically turn off a water pump** when the tank starts overflowing, without needing to manually access the switch. Ideal for bathrooms where sensor and switch are in different locations.

TARGET:
Easing manual handling of tank overflow at home using wireless connection b/w 2 esp32s (pipe and switch are in two different places)

- **Sensor Unit (Transmitter)**:
  - Placed inside or at the mouth of the overflow pipe.
  - Detects water using a water sensor.
  - Sends a wireless signal to the receiver unit.

- **Relay Unit (Receiver)**:
  - Installed near the switch in another washroom.
  - Receives signal from the transmitter.
  - Cuts off pump power via a relay module.

