# 🐶 Flappy Dog - Java Swing Edition

![Java Version](https://img.shields.io/badge/Java-25-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)
![IDE](https://img.shields.io/badge/IDE-IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)

**Flappy Dog**, inspired by the legendary Flappy Bird game, is developed using the Java Swing library. It is a modern, optimized game written in adherence to Object-Oriented Programming (OOP) principles.

This project demonstrates game loop, custom painting, and collision detection mechanics.

---

## 🎥 Preview

You can see the game's smooth mechanics below:

<img width="958" height="479" alt="Flappy Dog Gameplay" src="https://github.com/user-attachments/assets/c5c57516-64ca-40f6-acac-803b09b3bae1" />

---

## 🎮 How to Play? (Controls)

The game mechanics are entirely based on reflexes and timing.

| Key | Function | Description |
| :---: | :--- | :--- |
| **SPACE** | <kbd>Space</kbd> | Makes the dog jump. Used to counteract gravity. |
| **R** | <kbd>R</kbd> | Instantly restarts the game when Game Over occurs. |

---

## 🚀 Features

* ✅ **Java 25 Architecture:** Developed with the latest Java version.
* ⚡ **Smooth Physics Engine:** Realistic gravity and jumping feel.
* ⚖️ **Forgiving Hitbox System:** Collision boxes are set slightly smaller than visuals for a smoother and fairer gaming experience.
* 📊 **Scoring System:** Real-time score tracking and game over screen.
* 🎨 **Swing Graphics2D:** High-performance 2D drawing techniques.

---

## 📥 Download and Play (Ready-to-Use Version)

To play the game immediately without dealing with code, go to the **[Releases](https://github.com/ProGencel/FlappyDog/releases/latest)** page and download the package (`.zip`) suitable for your operating system.

### 🚀 How to Launch?

**Important:** Be sure to extract the contents of the downloaded `.zip` file into a folder. Running directly from inside the ZIP may cause errors.

#### 🪟 Windows Users:
1. Double-click the **`StartWin.bat`** file inside the folder.
2. *If a "Windows Protected Your PC" warning appears:*
   * Click on **"More Info"**.
   * Click **"Run Anyway"**.
   * *(This warning appears because the app is not digitally signed; it is safe.)*

#### 🍎 macOS and 🐧 Linux Users:
1. Right-click in an empty space inside the folder and select **"Open in Terminal"**.
2. Paste the following command and press `Enter` to grant permission to the launcher (only needed the first time):
   ```bash
   chmod +x StartMacLinux.sh
   ```

> **🛠️ For Developers:** If you only need the **`.jar`** file, it is also available standalone as `FlappyDog.jar` in the Releases section.

---

## 🛠️ Installation and Running (Build & Run)

This project uses **Java 25** features. Please ensure your JDK version is up to date.

### Requirements
* [Java Development Kit (JDK) 25](https://jdk.java.net/25/) or higher.
* Git (Optional, for cloning).

### Method 1: Terminal / Command Line (Recommended)

You can run the game without depending on any IDE as follows:

```bash
# 1. Clone the repo
git clone https://github.com/ProGencel/FlappyDog.git

# 2. Enter the project directory
cd FlappyDog

# 3. Create build directory and compile
mkdir -p bin
javac -d bin src/*.java

# 4. Start the game
java -cp bin Main
```
