<h1>⌨️ AULA LED Editor Ultimate</h1>

<h3>The definitive, feature-rich controller for the AULA mechanical keyboard collection's RGB lighting.</h3>
<details>
<summary><h2>✅ Compatability</h2></summary>
  Currently, the Aula F75 is the main supported keyboard. However, any keyboard in the Aula Suite can have a custom mapping assigned. 

  | Model Name | Compatibility |
| :--- | :---: |
| **F65** | ❌ |
| **F75** | ✅ |
| **F81** | ❌ |
| **F87** | ❌ |
| **F98** | ❌ |
| **F99** | ❌ |
| **F106Pro** | ❌ |
| **F108** | ❌ |
| **F815** | ❌ |
| **F2023** | ❌ |
| **F2068** | ❌ |
| **F2088** | ❌ |
| **F-NB98** | ❌ |
| **AMG65** | ❌ |
| **AU75** | ❌ |
| **EA75MAX** | ❌ |
| **H108** | ❌ |
| **L87** | ❌ |
| **L99** | ❌ |
| **M75** | ❌ |
| **NOVA75** | ❌ |
| **S75** | ❌ |
| **S98** | ❌ |
| **S100** | ❌ |
| **T102** | ❌ |
</details>
<details>

<summary><h2>❓ What?</h2></summary>

The Problem

The stock software provided for the AULA keyboards collection is functional, but limited. Painting custom lighting effects frame-by-frame or key-by-key is tedious, restricts your creativity, and lacks advanced tools like gradients or image projection.

The Solution

AULA Editor Ultimate is a "Ghost Controller." It provides a modern, web-based interface loaded with Photoshop-like tools (brushes, fills, gradients, plasma generators).

How it works:

You design your lighting theme in the web interface. When you click APPLY, the Python backend takes over your mouse and "physically" clicks the pixels into the original AULA software at lightning speed (Turbo Mode). It automates the tedious work, allowing you to apply complex mathematical patterns, images, and gradients in seconds.

</details>

<details>
<summary><h2>📷 Screenshots!</h2></summary>
<img width="1145" height="683" alt="Image" src="https://github.com/user-attachments/assets/7d02d2ee-8668-4d9b-b957-179c2734e14c" />

<img width="660" height="653" alt="Image" src="https://github.com/user-attachments/assets/e770bbf3-728b-4fcf-bf5d-8fba795fd3fc" />
</details>
<details>
<summary><h2>🎛️ Usage (pre-install)!</h2></summary>

The web interface is your command center. Here is what every knob, dial, and button does:

🎨 The Palette

PRI (Primary) & SEC (Secondary): Your two main colors. Click the circle to open the Pro Picker (Saturation/Brightness box), or type a Hex code directly.

Bright: Adjusts the brightness of your chosen colors globally (-100% to +100%).

Sat: Supercharges or drains color intensity. You can crank this to ±500% for deep-fried neon effects or grayscale looks.

Speed: Controls how fast the automation clicks. Positive values make it faster (for speed), negative values slow it down (for stability on slower PCs). 501% activates Ludicrous Mode.

🛠️ Tools

Brush: Standard painting. Left-click paints Primary color. Right-click paints Secondary color.

Fill: Floods the entire board with the selected color.

Gradient: Click once to set the Start Point, move your mouse to angle the direction, and click again to set the End Point.

Left-Click Sequence: Gradient goes Primary $\to$ Secondary.

Right-Click Sequence: Gradient goes Secondary $\to$ Primary.

Mirror Mode: Whatever you draw on the left side is instantly reflected onto the right side.

⚡ Generators

Checkers / Stripes: Instantly applies mathematical patterns using your two selected colors.

Plasma Cloud: Generates a unique, procedural nebula effect based on your Primary/Secondary colors.

Binary Evangelist: Instantly maps the sacred binary sequence 01001010... to your keyboard.

📷 Media & Library

Upload Image: Drag and drop an image to project it onto your keyboard keys (auto-pixelated).

Text: Type your name or a phrase to scroll it onto the keys.

Presets: One-click highlighting for FPS (WASD), MOBA (QWER), etc.

Save/Load: Save your masterpiece to your browser's local storage so you don't lose it.

🔌 The Backend Link

When you click APPLY PATTERN, the website sends a grid of color data to a Python script running in the background. That script wakes up, calculates the screen coordinates of your AULA software, and begins clicking the keys rapidly to match your design.

</details>

<details>

<summary><h2>📦 Installation+</h2></summary>

We have made installation effortless with a single script.

Download the installer batch file from releases.

Locate the install_and_run.bat file.

Run the file, Done!

Note: To run the file without reinstalling, you can run the file "run.bat"
</details>

<details>

<summary><h2>🚀 Usage (post-install)!</h2></summary>

Once the application is running, here is how to use it safely and effectively.

1. The Calibration (First Run Only)

When you run the app for the first time, it needs to know where the keys are on your screen.

Open your AULA Keyboard Software and select the "Custom Light" tab.

The script will ask you to hover your mouse over the Red, Green, and Blue text input boxes in the software and press Enter.

It will then ask you to hover over Key 1 (Esc) through Key 80 and press Enter for each. Make sure the command prompt is selected when pressing enter

While this is a tedious process, you'll only have to do it once

2. Applying a Design

Create your design in the web interface.

Click the big blue APPLY PATTERN button.

The Safety Countdown: A giant overlay will appear counting down from 5.


3. Re-Calibration

If you move the AULA software window or change your screen resolution, the clicks will miss.

If you wish to restart and recalibrate, simply say [n]o when you run the new-autorun batch file

Restart the application, and it will ask you to calibrate again.

</details>

<details>

<summary><h2>🌐 More</h2></summary>

This project is a proud part of Source Unlatched.

Source Unlatched is a collection of FOSS (Free and Open Source Software) applications designed to unlock the potential of your hardware and better your digital life without paywalls or bloatware.


</details>
<details>
<summary><h1>🚨 Emergency</h1></summary>
<h4>Hands Off: Move your mouse away. Do not touch the mouse or keyboard while the script is working. </h4>
<h3>If you forget to do something, such as clearing Aula Software, you can press ESC (escape) to cancel the process during the countdown.</h3>
<h2>Emergency Stop: If the script starts clicking the wrong things, or you forget something after the countdown, press F7 immediately to kill the process.</h2>
</details>
<details>
<summary><h2>Security</h2></summary>
<h4>Due to the way github limits file sizes to 25mb, the installation files zip installed with the autoinstaller (install_and_run.bat) are hosted on [google drive](https://drive.google.com/file/d/19G-wgcdYitwyy_NXgVzw5_2920_Zvg2U/view?usp=sharing).</h4>
</details>
