# FlintOS v2.6 🚀

FlintOS is an optimized, monolithic graphical micro-operating system engineered specifically for the resource-constrained **ATmega328P (Arduino Uno)** micro-controller. 

By aggressively implementing the `F()` macro for string literals and utilizing tight conditional loops, FlintOS packs a multi-screen framework, user security, and three real-time games into **under 2KB of SRAM**.

## 🛡️ Core Features
* **Custom Boot Engine:** Real-time hardware diagnostics and visual loading bar.
* **Lock Screen Security:** Secure 4-digit master passcode (`1021`) access panel with input wiping and visual error handling.
* **Flint Theme Engine:** Toggle instantly between high-contrast Dark Mode and crisp Light Mode across all applications.
* **Notes App:** A raw-resistor touch-polling sketchbook canvas supporting a custom 7-color palette array and canvas clearing.
* **System Apps:** Integrated utility panel with a reactive Flashlight app and dynamic shifting battery status bar.

## 🕹️ Integrated 8-Bit Arcade Deck
1. **Retro Race:** Lane-shifting traffic evasion game with dynamic speed acceleration and non-volatile EEPROM High Score tracking.
2. **Greedy Snake:** Grid-mapped matrix movement, random item spawning, self-collision checking, and head-rendering mechanics.
3. **Flap Bird:** Continuous scrolling physics engine with trailing edge anti-aliasing to eliminate screen ghosting.

## 🔧 Hardware Requirements
* **Microcontroller:** Arduino Uno (ATmega328P)
* **Display:** 2.8"/3.5" TFT LCD Shield (IL9341 Driver or compatible MCUFRIEND pinout)
* **Storage:** 32GB SD Card (Optional / Expandable for storage updates)(**IMPORTANT**:-*THIS IS NOT INCLUDED IN THIS CODE*)
* **SOUND:**  AS OF LOW RAM WE HAVE KEPT IT SIMPLE AND USE A 2 PIN BUZZER , ITS SMALL AND LIGHT , CONNECT THE (+) PIN TO GPIO 12 AND GND TO GROUND , FOR A SAFER SIDE I PREFER TO POWER IT FROM AN ADAPTER OF UR AND SOMETHING LIKE :- 
UNO R3'S DATA PORT CONNECT AND CONNECT IT TO ADAPTER 

## 📦 Core Libraries Used
* `Adafruit_GFX.h`
* `MCUFRIEND_kbv.h`
* `TouchScreen.h`
* `EEPROM.h`

## 🚀 How to Run
1. Clone this repository or download `FlintOS.ino`.
2. Connect your 2.8"/3.5" TFT Shield to your Arduino Uno.
3. Open the file in the Arduino IDE.
4. Ensure your display driver ID matches (FlintOS includes auto-fallback filtering for `0x9341`).
5. Compile and upload! (Default Master PIN: **1021**
## IF ANY QUERRY U MAY AS ME AT 
DISCORD(SORRY BUT IF I DONT ACCPET UR REQUEST PLZ TRY METHOD 2  ) :- https://discord.gg/YSMJAhyWu
THANK YOU !
