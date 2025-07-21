# Women Safety Device
## 📌Project Overview
This project proposes a compact, user-friendly safety device designed to enhance women's security, particularly in vehicles. Upon activation via a simple button press, the device generates an emergency alarm, acquires the user's precise GPS location, and immediately sends SMS alerts containing a Google Maps link to pre-defined emergency contacts (friends, family, or police). Additionally, it incorporates a buzzer for immediate audible alerts and a shock circuit for self-defense. Future enhancements include pulse rate monitoring and wireless connectivity. The system aims to provide real-time assistance and deter potential threats, contributing to a reduction in crime rates against women.
## ✨Features
⚪ GPS Tracking: Real-time location tracking.

⚪ SMS Alerts: Sends emergency messages with GPS link via GSM.

⚪ Microcontroller: Arduino-based central control.

⚪ User Activation: Simple button press with a unique periodic press feature.

⚪ Audible Alarm: Buzzer for immediate attention, remotely deactivatable.

⚪ LCD Display: Shows status and coordinates.

⚪ Shock Circuit: Provides self-defense.

⚪ Pulse Sensor (Optional): Monitors and transmits pulse rate.

⚪ Compact Design: User-friendly and portable.

## 🛠️Tech Stack
1. Hardware: Sensors(GPS Module,GSM Module,LCD Display,Buzzer,Push Button), Microcontrollers(Arduino uno)
2. Software: Arduino uno programming

## 🚀 Installation & Usage
🟢 ***Hardware Setup:***
1. Push Button: Connects to Arduino digital input (e.g., Pin 7) for activation.
2. GPS Module: Connects to Arduino via Software Serial (e.g., Pins 10, 11) for location data.
3. GSM Module: Connects to Arduino via Hardware Serial (Pins 0, 1) for SMS alerts; requires external power and SIM card.
4. LCD Display: Connects to Arduino via I2C (SDA, SCL) for visual feedback.
5. Buzzer: Connects to Arduino digital output (e.g., Pin 13) for audible alerts.
6. Shock Circuit: Separate module, likely controlled by Arduino via relay/transistor, requires independent high-voltage power.
7. Power Up: Supply power to Arduino and GSM module, then verify component functionality.

🟢 ***Software Setup:***

Installation of Arduino Ide
```bash
https://www.arduino.cc/en/software/
```
## 📌 Future Enhancements
1. Wireless: Bluetooth/Wi-Fi for app control, cloud tracking.
2. Activation: Biometric, voice, gesture control.
3. Communication: Two-way calls, live audio/video, multi-channel alerts.
4. Location: Indoor positioning, geofencing.
5. Sensors: Pulse, environmental, impact detection.
6. Design: Longer battery, rugged, wearable.
7. Integration: Direct emergency services link.

## 💡 Acknowledgments
A sincere thank you to our mentors, and the open-source community for their exceptional guidance and support.

📌 Feel free to contribute to AquaDox by submitting PRs or reporting issues! 🚀
