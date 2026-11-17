# Blendy × LIT ENERGY — Smoothie & Energy Flavour Slider Hero

Exact single-screen landing hero recreation for **LIT ENERGY** / **Blendy**. Full-viewport product slider with measured panel wipe transition, depth parallax, floating idle bobbing fruit elements, self-hosted fonts, responsive scaling, and official LIT Energy can designs.

## Live Demo
👉 **[View Live on GitHub Pages](https://dima11433.github.io/lit-energy-hero/)**

## Flavours
1. **Berry (Черника)** — `#C2B0DC` (soft lilac) with LIT ENERGY Черника (Выбор Бадаева) + raspberries, blueberries, blackberries.
2. **Kiwi / Citrus (Цитрусовый удар)** — `#B4D58A` (soft mint green) with LIT ENERGY Цитрусовый удар (Выбор Равшана) + kiwi round slices & wedges.
3. **Banana / Mango (Манго-Кокос)** — `#F3DA8A` (butter yellow) with LIT ENERGY Манго-Кокос (Выбор Анкалаева) + banana coins & chunks.
4. **Strawberry (Клубничная жвачка)** — `#F2AFC0` (pastel strawberry pink) with LIT ENERGY Клубничная жвачка (Выбор Оева) + fresh strawberries.

## Features
- **Exact Measurements**: 1440 × 900 design frame, `--u` scaling system (`min(viewportWidth / 1440, viewportHeight / 900)`), and `--n` UI scaling unit.
- **Measured Panel Wipe Transition (970 ms)**: Slow start, fast rush, and long soft settle according to the measured coverage table with smoothstep interpolation (`3k² - 2k³`).
- **5-Layer Depth Parallax**: Word (0.40), Shadow (0.30), Bottle (0.15), Fruit (0.55), Corner (0.75).
- **Idle Motion**: Alternate infinite ease-in-out bobbing with random duration (3.2s–5.0s) and random negative delay (0s to -4s) so pieces never move in step.
- **Dynamic Cap Line Typography**: Poppins 700 with canvas ink width measurement, auto-condensing letter-spacing, and aligned cap center line.
- **Official LIT ENERGY Branding**: Vector SVG logo, 1080×1920 RGBA transparent cans from [litenergy.ru](https://litenergy.ru/drinks).
- **Controls**: Autoplay every 2.6s (pauses 6s on interaction), keyboard arrows, touch/pointer swipe gestures, tabs with gliding underline (0.6s cubic-bezier(0.65, 0, 0.35, 1)).
- **Dual Mode**: Switch between official LIT ENERGY cans and original smoothie bottle cutouts with the top right toggle.
- **Dual Language**: Switch between EN (`Berry`, `Kiwi`, `Banana`, `Strawberry`) and RU (`Черника`, `Цитрус`, `Манго`, `Клубника`).
- **Responsive Layout**: Desktop full frame + tablet/mobile adaptation (`<= 820px` or portrait) with two-row header and centered controls.
- **Zero Dependencies**: Pure HTML5, inline CSS, and vanilla JavaScript.
