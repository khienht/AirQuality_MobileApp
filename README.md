<!-- Header -->
<h1 align="center"><b>Indoor Air Quality Monitoring Application</b></h1>
An Android application designed to monitor indoor air quality and provide users with real-time environmental data including temperature, humidity, wind speed, and rainfall.

## Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Demo](#-demo)
- [License](#-license)

## 📱 Overview

This mobile application was developed as part of the *Mobile Application Development* course (NT118.O14.MMCL) at UIT - University of Information Technology, VNU-HCM.

- **Semester**: Semester 1, Year 3  
- **Group**: 13
- **Group Members**:
  - Nguyễn Như Hà - 21522028  
  - Hồ Thị Khánh Hiền - 21522057

## 🚀 Features

### 🔐 Authentication
- User **Sign Up** and **Log In** functionality.
- **Note**: After signing up, the app must be restarted due to automatic login through WebView.
- Each Gmail account can register only **once**.
- **Duplicate usernames are not allowed**.

### 🌐 Language Support
- Supports **English** and **Vietnamese**.

### 🏠 Home Fragment
- Displays basic air quality data:
  - Username
  - Temperature
  - Humidity
  - Wind Speed
  - Rainfall

### 🗺 Map Fragment
- Shows device location and details.
- Integrated with **Google Maps API**.

### 📈 Chart Fragment
- Visualizes air quality data using **LineChart**.
- Data retrieved via API calls to asset datapoints.

### 👤 User Fragment
- Displays user account details.
- Allows users to submit feedback on weather conditions.

### 🗣 Feedback Fragment
- Users can:
  - Submit feedback about current weather conditions.
  - View feedback from other users.
- Data is stored in a **database**.

## 🛠 Tech Stack

- **Platform**: Android  
- **Language**: Java  
- **UI Design**: Figma  
- **APIs**:  
  - **Google Maps API**  
  - **Custom Weather/Air Quality API** (provided by course instructors) 
- **Libraries**: LineChart Library  

## 📸 Demo

A complete walkthrough of the application is provided through this [link](https://drive.google.com/file/d/1yKAtOF0b9m9hLb8xwWBdoj0oIlAd-3Q8/view?usp=sharing).

You can also view the project presentation via this [link](https://github.com/khienht/AirQuality_MobileApp/blob/main/Documents/AirQuality_MobileApp.pdf).

## 📄 License

This project was developed for academic purposes and is not intended for commercial use.
<!-- Footer -->
`Copyright © 2025 - Hồ Thị Khánh Hiền`
