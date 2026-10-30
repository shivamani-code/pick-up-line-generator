# 💘 Pick-Up Line Generator

A playful single-page web app that greets you by name and serves random cheesy pick-up lines over an animated, emoji-filled background.

## ✨ Features

- **Welcome screen** – asks for your name before starting (with a prompt if left empty)
- **Personalised greeting** – "Welcome, <your name>!"
- **Random pick-up lines** – 14 built-in lines, never the same one twice in a row
- **Animated background** – shifting gradient with 30 floating emojis (😍 💖 ✨ 🔥 …)
- **Frosted-glass UI** – blurred, translucent card with glowing buttons

## 🛠️ Tech Stack

- HTML5
- CSS3 (keyframe animations, `backdrop-filter`)
- Vanilla JavaScript

No frameworks, no build step, no dependencies.

## 📁 Project Structure

```
pick-up-line-generator/
├── pip_up_line.html   # The whole app (markup, styles, script)
└── pick_up.zip        # Zipped copy of the page (pick_up.html)
```

## 🚀 Run Locally

```bash
git clone https://github.com/shivamani-code/pick-up-line-generator.git
cd pick-up-line-generator
```

Then open `pip_up_line.html` in any browser.

## 🧩 Customise

Add your own lines to the `pickupLines` array in the `<script>` block of `pip_up_line.html`.
