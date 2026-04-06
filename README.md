# 🗺️ UIKit MapKit Demo

A UIKit app demonstrating how to embed an interactive map using `MKMapView`, add annotations, and respond to user location — all in programmatic UIKit without storyboards.

---

## 🤔 What this is

This project shows how to use MapKit in a UIKit app: displaying a `MKMapView`, centering on a coordinate, dropping `MKPointAnnotation` pins, and handling annotation tap callbacks via `MKMapViewDelegate`. It also covers requesting location permissions and centering the map on the user's current position.

## ✅ Why you'd use it

- **MKMapView** — embed and configure an interactive map programmatically
- **MKPointAnnotation** — drop pins with custom titles and subtitles
- **MKMapViewDelegate** — respond to annotation selection and map region changes
- **User location** — request `NSLocationWhenInUseUsageDescription` and center on current position
- **No storyboard** — fully code-based UIKit setup

## 📺 Watch on YouTube

[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch%20the%20Tutorial-red?style=for-the-badge&logo=youtube)](https://youtu.be/txsX27k8J6M)

> This project was built for the [NoahDoesCoding YouTube channel](https://www.youtube.com/@NoahDoesCoding97).

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/NDCSwift/UIKitMapKitDemo.git
cd UIKitMapKitDemo
```

### 2. Open in Xcode
- Double-click `MapKitDemoUIKit.xcodeproj`

### 3. Set Your Development Team
In Xcode: **TARGET → Signing & Capabilities → Team**

### 4. Update the Bundle Identifier
Change `com.example.MyApp` to a unique identifier (e.g., `com.yourname.MapKitDemo`).

---

## 🛠️ Notes

- `NSLocationWhenInUseUsageDescription` must be set in Info.plist to request location access.
- If you see a code signing error, check that Team and Bundle ID are set.

## 📦 Requirements

- iOS 16+
- Xcode 15+
- Swift 5.9+

---

📺 [Watch the guide on YouTube](https://youtu.be/txsX27k8J6M)
