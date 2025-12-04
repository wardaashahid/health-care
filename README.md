# health-care
This project is a complete console-based Health &amp; Wellness Tracking System built using Object-Oriented Programming (OOP) concepts in C++. It records daily health metrics, calculates scores, manages medical history, detects warnings, and generates personalized reports all in one program.
🚀 Features
✅ User Profile & Medical Information

Store name, age, and auto-generated User ID

Input height, weight, and calculate BMI

Enter chronic diseases

Record family medical history
(Heart disease, diabetes, asthma, obesity, etc.)

📊 Daily Health Metrics

The user can record multiple metrics:

Steps

Heart rate (with bradycardia/tachycardia warnings)

Calories

Sleep duration

Water intake

Daily weight

Each metric is stored through polymorphism using a HealthMetric base class and derived classes.

😄 Emotion & Mood Tracking

User can record daily emotional state
(happy, stressed, sad, angry, neutral)

🤒 Symptom Tracking

Describe symptoms with severity (1–10)

Automatic advice:

Mild → “Take rest and medicine”

Severe → “Seek medical attention!”

📈 Daily Health Score System

Calculates a score out of 100 based on:

Steps

Sleep

Water intake

Mood

Additional conditions (BMI, calories, sleep issues)

🥗 Smart Recipe Suggestions

Recipes categorized by tags:

Low-calorie

High-protein

Heart-friendly

Vegetarian

Fiber-rich

User searches by preference.

📄 Daily Health Report

Generates a complete summary:

BMI + interpretation

Family history

All metrics

Warnings

Emotions

Symptoms

Suggestions

Overall daily score

🧭 User-Friendly Menu System

Add metrics

Add emotions

Add symptoms

View report

Get recipe suggestions

View status summary

Exit

🛠️ Technical Concepts Used
🎯 C++ OOP Concepts

Classes & Objects

Encapsulation

Inheritance

Virtual functions

Abstract classes

Polymorphism (runtime)

Dynamic memory (new, delete)

Arrays of object pointers

Composition (User → MedicalInfo → FamilyHistory)

🧮 Input Validation

Strict ranges for:

height

weight

heart rate

calories

water intake

symptoms severity

🖨️ Formatting

iomanip for precision output

Clean menu-driven output

📦 File

All logic is contained in a single main.cpp for easy compilation.

▶️ How to Run
g++ main.cpp -o tracker
./tracker

📌 Future Enhancements (Optional)

File handling (save/load user data)

Ranking multiple users

Graphs (steps, sleep, weight trends)

Login system

Export report to file
