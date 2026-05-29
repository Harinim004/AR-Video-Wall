# 📺 AR Video Wall (Unity AR Project)

The AR Video Wall is an Augmented Reality application built using Unity that allows users to place a virtual video screen on real-world surfaces. It supports remote video streaming, dynamic video switching, and cloud-based content management using Addressables and Firebase.

---

## 🚀 Features

- 📱 AR-based wall detection using AR Foundation  
- 🎥 Virtual video screen placed on real-world surfaces  
- 🌐 Remote video loading using Addressables  
- 🔁 Video switching with UI buttons  
- ⚡ Smooth playback using Unity VideoPlayer  
- ☁️ Firebase integration for hosted video streaming  

---

## 🛠️ Setup Instructions (ZIP File)

1. Download the ZIP file from this GitHub repository  
2. Extract the ZIP file to your local system  
3. Open **Unity Hub**  
4. Click **Open Project**  
5. Select the extracted project folder  
6. Wait for Unity to import all packages and resolve dependencies  
7. Open the main scene
8. Connect an AR-supported Android/iOS device  
9. Click **Build & Run** to test the project  

---

## 📦 Addressables Configuration

1. Go to:
   Window → Asset Management → Addressables → Groups
2. Create a group:
   RemoteVideos

3. Add video assets and assign keys:
- `video1`
- `video2`

4. Set **Remote Load Path** for cloud delivery

5. Build Addressables:
   Build → New Build → Default Build Script

   
📌 This enables remote video loading without rebuilding the app.

---   
## 📱 Build Requirements

- Android: ARM64 + IL2CPP  
- ARCore / ARKit supported device required  
- Internet connection required for remote Addressables loading  
- Good lighting conditions recommended for stable AR tracking

      
