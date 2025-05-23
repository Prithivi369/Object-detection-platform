
# Object Detection Platform

This project is an object detection platform built using JavaFX for the frontend, OpenCV for webcam integration, and BLIP API for real-time object detection.

## Project Overview

This platform provides a GUI-based application for object detection using a webcam. It integrates the BLIP to detect various objects in real-time and display the results on the screen.

---

## Technologies Used
- **Java** (with JavaFX for GUI)
- **OpenCV** (for webcam integration)
- **BLIP API** (for real-time object detection)
- **IntelliJ IDEA** (for development)

---

## Setup Instructions

### Prerequisites:
1. **Java 17 or higher**: Make sure that Java is installed on your machine. You can download it from the [official site](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html).
   
2. **OpenCV**: You need to set up OpenCV for Java in your project. You can download the OpenCV Java library from the [OpenCV official website](https://opencv.org/releases/).

3. **JavaFX**: Download JavaFX SDK from [Gluon](https://gluonhq.com/products/javafx/) and configure it with your project.

---

### Setting Up the Project:

### 1. Install Requirements
- Java JDK 17 (or specify whatever you're using)
- JavaFX SDK (download from Gluon)
- OpenCV (with Java bindings)

### 2. Set Up in IntelliJ IDEA
- File → Project Structure → Project SDK → Add JDK
- File → Project Structure → Libraries → Add JavaFX and OpenCV JARs
- Right-click `src/` → Mark Directory as → **Sources Root**
- Right-click `resources/` → Mark Directory as → **Resources Root**


### Running the Application

1. **Setup JavaFX**:
   - Add the JavaFX SDK as a library.
   - Set the VM options with the correct `--module-path` and `--add-modules` settings.

2. **Setup OpenCV**:
   - Add OpenCV jar and set the native library path.

3. **Run the Application**:
   - Once dependencies are configured, run `Main.java` from IntelliJ IDEA.

### Folder Structure

- **Main.java**: The main entry point of the project.
- **style.css**: Application-specific styling.

## 🛠️ Notes
- This project does not yet use Maven/Gradle.
- All dependencies must be set manually as mentioned above.



