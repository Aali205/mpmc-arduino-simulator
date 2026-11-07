# MPMC Arduino Lab Simulator

**محاكي تجارب الأردوينو لمادة MPMC**

Practice the MPMC Arduino lab experiments in your browser without a board. Wire the circuit, write real Arduino code, upload it, and watch the LEDs, button, potentiometer, buzzer and LDR react.

![Screenshot](docs/screenshot.png)

## Features

- **10 lab experiments:** blink, button → LED, PWM fade, fade on button press, potentiometer → brightness, potentiometer → blink speed, buzzer, toggle, traffic light and LDR night light.
- **Realistic wiring:** pick pins, resistors and LED direction. A missing resistor burns the LED, a reversed LED stays dark, and a missing pull-down makes the button pin float.
- **Real Arduino code:** `pinMode`, `digitalWrite`, `digitalRead`, `analogWrite`, `analogRead`, `map`, `delay`, `tone`, `Serial`, and your own functions and arrays.
- **IDE-style errors** for common mistakes: missing `;`, `pinmode` instead of `pinMode`, `Void`, unclosed `{`, and `=` instead of `==`.
- **Circuit diagram** for every experiment, to compare with your own drawing.
- **Exam mode:** a random experiment, an empty sketch and a 15-minute timer.
- **Serial Monitor**, a pin plotter that shows the PWM wave, and a choice of **Mega 2560** or **Uno**, with the correct PWM pins for each.

## Visit counter

The header shows how many times the site was opened and by how many different people. It only counts on the GitHub Pages site.
Open `https://aali205.github.io/mpmc-arduino-simulator/?me` once on each of your own devices so your visits are not counted.

## Use it

Open `index.html` in any browser. You don't need to install anything.

To get a link you can share, turn on GitHub Pages: **Settings → Pages → Branch: `main` / root → Save**. The site will then be at `https://<your-username>.github.io/mpmc-arduino-simulator/`.

## طريقة الاستخدام

1. اختر التجربة من القائمة.
2. وصّل القطع من لوحة **Wiring** (الرجل الطويلة للّيد باتجاه الـ pin، مقاومة 220Ω للّيد، و10kΩ pull-down للزر).
3. اكتب الكود واضغط ➜ **Upload**.
4. جرّب: اضغط الزر أو حرّك المقاومة المتغيرة.
5. استخدم **Exam mode** للتدرّب قبل الامتحان.

## Note

This is a study tool. It simulates the behaviour of the lab circuits; it is not a full electrical or AVR emulator.
