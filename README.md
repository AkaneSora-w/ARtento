# ARtento

An Augmented Reality (AR) mobile application designed to improve attention, memory, and reaction skills through interactive exercises.

Developed as part of a Master's degree exam in Computer Science (Information Visualization course, a.y. 2025/2026).

---

## 📌 Overview

ARtento is an AR-based cognitive training application built with Unity and AR Foundation.  
It aims to overcome the limitations of traditional cognitive training tools (e.g. static 2D apps or paper exercises) by providing a more immersive, interactive, and engaging experience.

By integrating virtual objects into the real environment, the application stimulates multiple cognitive processes simultaneously, including:

- Selective attention  
- Visuo-spatial memory  
- Reaction time  

---

## 🎮 Features

- 📱 Mobile AR application (Android - ARCore)
- 🧠 Cognitive training through interactive exercises
- 🎯 Visual search game (attention & reaction)
- 🧩 Spatial memory game
- 📊 Performance tracking and feedback
- ⚡ Adaptive difficulty based on user performance
- 🏆 High score system (Top 3 leaderboard)

---

## 🧠 Exercises

### 🔴 Visual Search
- Focuses on **selective attention and processing speed**
- The user must identify target objects while ignoring distractions
- Difficulty dynamically adapts based on performance

### 🧩 Memory (Spatial Memory)
- Focuses on **visuo-spatial memory**
- The user interacts with objects placed in real space
- Requires movement and spatial awareness

---

## 🏗️ System Architecture

The application is structured into modular components:

- **AR Module**  
  - AR Session & AR Session Origin  
  - Plane detection using AR Foundation  

- **Game Logic**  
  - BaseExerciseManager (shared logic)  
  - Exercise-specific managers (VisualSearch, Memory)  

- **Interaction System**  
  - Gesture-based input (tap, raycasting)  
  - SelectableObject system  

- **UI/UX Layer**  
  - Timer, score, feedback  
  - Results and statistics visualization  

---

## ⚙️ Technologies

- **Engine:** Unity 6 (6000.0.59f2)  
- **AR Framework:** AR Foundation  
- **XR Plugin:** ARCore  
- **Language:** C#  
- **Platform:** Android  

---

## 📲 How It Works

1. **Environment Scanning**  
   The app detects real-world surfaces using AR plane detection.

2. **Scene Placement**  
   The user places the AR scene with a tap.

3. **Interaction**  
   Objects are interacted with using touch and raycasting.

4. **Feedback & Results**  
   Immediate feedback is provided, followed by performance statistics.

---

## 🎯 Target Users

- Children (cognitive training in a playful way)  
- Students  
- Users with attention difficulties  
- Cognitive rehabilitation contexts  

---

## 🚀 Future Work

- Integration with Machine Learning (ML-Agents)  
- Personalized training based on user behavior  
- More exercises and cognitive tasks  
- Improved data visualization  

---

## 📦 Download

The APK is available in the **Releases** section of this repository.

---

## 📄 License

This project was developed for academic purposes.
