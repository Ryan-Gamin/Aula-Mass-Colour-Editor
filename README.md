⌨️ AULA F75 Editor Ultimate

The definitive, feature-rich controller for the AULA F75 mechanical keyboard RGB lighting.

<details>

<summary><h2>❓ What?</h2></summary>

The Problem

The stock software provided for the AULA F75 is functional, but limited. Painting custom lighting effects frame-by-frame or key-by-key is tedious, restricts your creativity, and lacks advanced tools like gradients or image projection.

The Solution

AULA F75 Editor Ultimate is a "Ghost Controller." It provides a modern, web-based interface loaded with Photoshop-like tools (brushes, fills, gradients, plasma generators).

How it works:

You design your lighting theme in the web interface. When you click APPLY, the Python backend takes over your mouse and "physically" clicks the pixels into the original AULA software at lightning speed (Turbo Mode). It automates the tedious work, allowing you to apply complex mathematical patterns, images, and gradients in seconds.

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

Download this repository.

Locate the install_and_run.bat file.

Double click it.

The script will automatically:

Check for Python.

Create a dedicated subfolder called Aula F75 Editor Ultimate.

Install all required dependencies (Flask, PyAutoGUI, etc.) in an isolated environment.

Launch the application.

No manual command line work is required.

</details>

<details>

<summary><h2>🚀 Usage (post-install)!</h2></summary>

Once the application is running, here is how to use it safely and effectively.

1. The Calibration (First Run Only)

When you run the app for the first time, it needs to know where the keys are on your screen.

Open your AULA Keyboard Software and select the "Custom Light" tab.

The script will ask you to hover your mouse over the Red, Green, and Blue text input boxes in the software and press Enter.

It will then ask you to hover over Key 1 (Esc) through Key 80 and press Enter for each.

This creates a aula_mapping.json file. You only do this once!

2. Applying a Design

Create your design in the web interface.

Click the big blue APPLY PATTERN button.

The Safety Countdown: A giant overlay will appear counting down from 5.

Hands Off: Move your mouse away. Do not touch the mouse or keyboard while the script is working.

Emergency Stop: If the script starts clicking the wrong things, press ESC immediately to kill the process.

3. Re-Calibration

If you move the AULA software window or change your screen resolution, the clicks will miss.

Simply delete the aula_mapping.json file in the folder.

Restart the application, and it will ask you to calibrate again.

</details>

<details>

<summary><h2>🌐 More</h2></summary>

This project is a proud part of Source Unlatched.

Source Unlatched is a collection of FOSS (Free and Open Source Software) applications designed to unlock the potential of your hardware and better your digital life without paywalls or bloatware.

Visit Source Unlatched

(Link currently directs to FOSS definition - Official site coming soon)

</details>
