# 🎮 FNaF 1 PSP v1.5.4  

A **PlayStation Portable (PSP) port** of *Five Nights at Freddy’s* (FNaF 1).  
This release has been fully re-worked and optimized for smoother performance on PSP hardware and emulators.

(Originally a fork of the port created by BasDev: https://basdev.itch.io/fnaf1psp)   

---

## 📌 Release Notes (v1.5.4)
- Bugfix: All cameras visible from beginning of night
- Improvements to Runtime (Only cameras with a new image will be processed)
- Improved Horror Aesthetic 😉 

## v1.5.3 Release Notes
- 128px sprite slices (50% fewer draw calls vs version 1.5.2)
- 16-byte aligned memory allocation
- 333MHz CPU clock enabled
- Enabled Frame skip counter for intensive scenes (helps maintain 60fps)

## v1.5.2 Release Notes
- Corrected a potential memory leak in vram
- Race conditions removed within Audio, Camera & Jumpscare logic (prevents potential crashes when hardware is being overwhelmed)

## v1.5.1 Release Notes
- Tweaked some compile flags for smaller & faster C++ code
- Adjustments to audio assets (slightly smaller filesizes with noticeable improvements to audio quality)
- Less I/O hungry for smooth & stable gameplay during later levels or custom night   

---

## 📥 Installation
1. Download the latest release.  
2. Place the folder **`FNaF 1 PSP v1.5`** inside your PSP’s `/PSP/GAME/` directory.  
3. Custom firmware is **required** to play.  

---

## 🧪 Testing
- ✅ **PPSSPP Emulator**  
- ✅ **PSP-3000** (tested with ARK4 v6.60 custom firmware)  

---

## ⚠️ Disclaimer
*"Five Nights at Freddy’s"* is a game created by **Scott Cawthon**.  
This is an unofficial **fan-made port** for PSP. I claim no ownership of the original game or its assets.  

---

👤 **Created by:** CesarR70
