# DuckHunt-UNITY-
This contains the Package of game, U can access by importing the package in the asset menu of Unity Engine.


# 🦆 Duck Hunt Game using Unity Engine 🎮

## 🎯 Overview

The **Duck Hunt Game** 🦆🔫 is a classic arcade-style shooting game where players aim and shoot flying ducks in a limited time frame ⏳ to score points 🏅. Inspired by the retro NES classic, this version is rebuilt in **Unity Engine** 🎮 for modern devices, offering smooth gameplay, fun visuals 🎨, and engaging challenges on **Android** 📱.

---

## 🕹️ How It Works

In the Duck Hunt Game, ducks 🦆 appear on the screen, flying across the sky ☁️ at random speeds and directions ➡️⬅️. The player uses touch input 👆 to aim the crosshair 🎯 and tap to shoot 🔫. Each hit 🏹 earns points, and missing too many ducks may cost the player the game ⌛. As levels progress, ducks fly faster 💨 and appear more frequently, testing the player’s reflexes ⚡ and accuracy 🎯.

---

## 🛠️ How It’s Done with Unity

1. **Duck Prefabs 🦆📦:**  
   Each duck is created as a prefab:
   - Animated sprite sheets for flapping wings 🐥
   - RigidBody2D and Collider2D for physics and hit detection 🎯
   - Script to handle movement patterns, spawning, and destruction 💥

2. **Crosshair & Shooting 🎯🔫:**  
   A custom crosshair sprite replaces the default cursor 👆. The player moves the crosshair with touch input 📲 and taps to fire shots 🔫. A shooting script checks if a duck’s collider was hit and plays hit or miss effects ✅❌.

3. **Spawn Manager 🧩:**  
   Ducks are spawned by a manager script 🗂️ that:
   - Randomizes spawn position and flight direction 🔀
   - Controls the speed and frequency based on level difficulty 📈
   - Destroys ducks that fly off-screen to save resources ⚡

4. **UI & Score System 📊:**  
   Unity’s Canvas 🖌️ handles:
   - Scoreboard 🏅 showing total hits and misses
   - Remaining shots counter 🎯
   - Level progression and timers ⏱️
   - Start, Pause ⏸️, and Restart 🔄 buttons

5. **Animations & Effects ✨:**  
   Smooth animations for flying 🕊️ and hit reactions 💥 make the game exciting. Add muzzle flash 🔥 and gunshot sounds 🔊 for shooting feedback. Backgrounds 🌄 can change with levels for visual variety 🎨.

6. **Audio 🔊:**  
   Add satisfying effects for shots 🔫, quacking 🦆, and background forest or field sounds 🌳 for immersion.

7. **Build & Deploy 🚀:**  
   Unity makes it easy to test gameplay on real Android devices using **Unity Remote** 📲 and export the finished game as an APK/AAB for installation or upload to the Google Play Store 🏪.

---

## 🌟 Features

✅ Classic arcade shooting gameplay 🔫  
✅ Randomized duck patterns for replay value 🔀  
✅ Increasing difficulty with faster ducks 💨  
✅ Fun sound effects and animations 🎶✨  
✅ Touch controls optimized for Android devices 📱

---

## 📈 Why Unity?

Unity Engine 🎮 provides an ideal platform for building an arcade shooter like Duck Hunt 🦆. With its robust 2D tools 🧰, animation system 🎞️, and flexible physics engine ⚙️, developers can recreate the feel of the retro game while adding modern polish 🌟. The Asset Store 🛍️ offers free and paid sprites, sound packs 🔊, and tools to speed up development 🧩.

---

## 🎉 Conclusion

Building a Duck Hunt 🦆🎯 game with Unity for Android 📱 is a fun way to learn about 2D animation, physics, input handling, and game design fundamentals 🎓. Players get to test their reflexes ⚡ and accuracy 🎯 while enjoying nostalgic, lighthearted shooting fun 🔫 anytime, anywhere 🌍.

---

**🚀 Ready, aim, shoot — let’s hunt some ducks! 🦆🎯🔫**

