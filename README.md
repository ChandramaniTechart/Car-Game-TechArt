# 🚗 Technical Artist Assignment – Unity Endless Runner

## 📌 Overview
This project focuses on enhancing a basic **Unity endless runner prototype** by improving its visual quality, lighting, and overall game feel while maintaining performance suitable for mobile devices.

The core gameplay (auto-moving car with lane switching) was already provided. My role was to elevate the project visually and technically to a **production-ready standard**.

---

## 🎯 Goals
- Improve visual quality and scene composition  
- Optimize the project for mobile performance (stable FPS)  
- Enhance game feel with visual feedback  
- Maintain a stylized arcade aesthetic  

---

## 🎨 Environment & Visual Improvements
- Replaced the basic prototype environment with a stylized city scene  
- Used assets from the Unity Asset Store and optimized them  
- Maintained a consistent warm and vibrant color palette  
- Improved:
  - Road readability  
  - Scene depth using fog  
  - Overall visual clarity  

---

## 💡 Lighting Setup
- Directional Light set to Mixed Mode (Baked Indirect)  
- Implemented baked lighting to reduce runtime cost  

### Key Adjustments:
- Ambient lighting balance  
- Fog color for depth perception  
- Optimized shadow settings for mobile  

### Result:
- Bright, stylized high-key look  
- Improved depth and visibility  

---

## ⚙️ Optimization Work

### Rendering Optimizations:
- Static Batching enabled  
- GPU Instancing used where applicable  

### Asset Optimization:
- Textures:
  - Reduced resolution  
  - Applied compression  
- Materials:
  - Minimized material count  
  - Reduced draw calls  
- Shaders:
  - Used lightweight/mobile-friendly shaders  

### Shadow Optimization:
- Reduced shadow distance  
- Disabled shadows on smaller props  

---

## ✨ Game Feel Enhancements

### 🚗 Car Tilt System
- Smooth tilt when switching lanes (left/right)

### 💨 Dust Particle FX
- Triggered during lane switch for better feedback  

### 🔧 Additional FX (Prepared)
- Trail effect  
- Spark effect (for future interactions)  

---

## 🚗 Assets Used
- Car & Road → Provided in assignment  
- Environment Assets → Unity Asset Store (Free stylized packs)  

### Optimization Applied:
- Reused assets efficiently  
- Reduced material usage  
- Optimized textures and meshes  

---

## ⚠️ Known Issues

### Road Spawning Gap
- Small visible gap appears between spawned road segments  
- Cause: Spawning logic (not visual issue)  
- Requires developer-side fix  

---

## 🧠 Role & Contribution
As a Technical Artist, my focus was on:

- Scene composition & layout  
- Lighting and mood  
- Performance optimization  
- Visual polish and feedback systems  

> Note: Core gameplay logic was not modified.

---

## 🚀 Future Improvements
- Cinemachine camera polish  
- Dynamic FOV based on speed  
- Improved VFX (collision & UI feedback)  
- Road spawning visual blending (if logic updated)  

---

## 🎯 Conclusion
This project transforms a basic prototype into a:

- ✔ Visually polished experience  
- ✔ Optimized mobile-ready build  
- ✔ More engaging gameplay feel  

With further development support, it can be extended to a production-quality mobile game.

---

## 📎 Notes
This work reflects a Technical Artist pipeline approach, focusing on:
- Bridging visuals and performance  
- Delivering optimized assets  
- Enhancing player experience  
