# 🎬 Промт для 3D-анимации

Источник: Notion → «Промт для 3D Анимации»

## Универсальный промт (для любого изображения → 3D-анимация)

```
Cinematic 3D animation generated from this reference image, preserving the exact composition, proportions, color palette, lighting style and materials of the original.

Bring the scene to life: identify every mechanical, electronic, natural and living element in the image and animate it according to its real-world physical behavior.

- Mechanical parts (gears, wheels, pistons, levers, pumps, rotors, hinges) move exactly as they would in real operation — rotating, swinging, pumping, or oscillating at a natural mechanical rhythm.
- Lights, screens, indicators and displays are active: blinking, glowing, pulsing, or showing live-updating content (charts drawing, bars growing, signals flickering).
- Liquids, smoke, fire, steam or energy effects flow and move naturally, following real fluid and volumetric dynamics — no static or frozen textures.
- Fabric, hair, leaves, grass, water, flags, dust or particles react naturally to implied air movement — gentle swaying, rippling, or drifting.
- Living beings (people, animals) show subtle, natural life-like motion: breathing, blinking, small weight shifts, gentle head or hand movement, natural micro-expressions — never robotic, exaggerated or looping unnaturally.
- Background elements (clouds, water, distant motion) drift slowly to add depth, without distracting from the main subject.

[ЗДЕСЬ ОПИШИТЕ 2–3 КОНКРЕТНЫХ ДВИЖЕНИЯ ДЛЯ ВАШЕЙ КАРТИНКИ, например: "the crane arm slowly rotates and lowers its hook", "the person gently turns their head and blinks", "water in the fountain continuously flows and splashes"]

Camera: slow, smooth, continuous orbital rotation around the scene, 180 to 360 degrees, constant speed, cinematic and stable — no shake, no jump cuts. If a full 360-degree rotation is used, the camera returns exactly to its starting angle for a perfectly seamless loop.

Style: photorealistic/high-detail 3D rendering matching the original image's aesthetic, consistent lighting throughout the rotation, glossy and natural material response to light.

Duration: 8–10 seconds, 16:9 aspect ratio, seamless loop, no distortion, no morphing artifacts, no flickering geometry.
```

## Негативный промт

```
distorted geometry, unnatural motion, robotic movement, flickering artifacts, warped shapes, blurry text, camera shake, inconsistent lighting
```

## Как использовать

- Загрузите исходное изображение как стартовый кадр (image-to-video) в Kling AI 3.0, Runway Gen-4.5 или Luma Dream Machine
- Замените блок в квадратных скобках на 2–3 конкретных движения именно вашей картинки
- Формат: 16:9, длительность 8–10 сек, seamless loop

## Вариант камеры: покачивание туда-обратно

(запасной, если 360° даёт шов на стыке лупа) — заменить абзац Camera на:

```
Camera performs a slow, smooth back-and-forth swinging motion — gently orbiting to one side, then reversing direction and returning exactly to the starting position, like a slow pendulum, creating a perfectly seamless loop with no jump cut.
```
