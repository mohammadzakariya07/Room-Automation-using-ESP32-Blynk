/*******************************************************
 * CIRCUIT DESIGN – ROOM AUTOMATION (ESP32 + RELAYS)
 *
 * Controller  : ESP32 Dev Module
 * Relay Type  : 4-Channel Relay (Active LOW)
 * Power       : 5V Relay Supply (External Recommended)
 *
 * ---------------- CONNECTIONS ----------------
 *
 * ESP32 GPIO  →  Relay Module  →  Appliance
 * ---------------------------------------------
 * GPIO 16     →  IN1           →  Fan 1
 * GPIO 17     →  IN2           →  Fan 2
 * GPIO 23     →  IN3           →  Light 1
 * GPIO 25     →  IN4           →  Light 2
 *
 * ESP32 GND   →  Relay GND
 * ESP32 5V    →  Relay VCC
 *
 * ---------------- AC LOAD SIDE ----------------
 *
 * AC LIVE  →  COM (Relay)
 * NO       →  Appliance LIVE
 * AC NEUTRAL → Direct to Appliance
 *
 * ---------------- LOGIC ----------------
 *
 * Relay is ACTIVE LOW:
 *   LOW  → Relay ON
 *   HIGH → Relay OFF
 *
 * ---------------- SAFETY ----------------
 * ⚠️ Use proper insulation
 * ⚠️ Do NOT touch AC terminals while powered
 * ⚠️ Use relay module with opto-isolation
 *
 *******************************************************/
