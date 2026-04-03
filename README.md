📱 MPTA – Monitoring and Payment Tracker Application

A smart Android application that monitors incoming SMS messages and tracks payment-related transactions automatically. This app is designed to help users keep a record of financial activities such as payments, credits, and debits directly from SMS notifications.

🚀 Features
📩 SMS Monitoring
Listens to incoming SMS messages in real-time
Detects transaction-related messages
💰 Payment Tracking
Extracts payment details from SMS
Tracks credits and debits
🔍 Transaction Insights
Helps users monitor financial activity
Can be extended for analytics and summaries
⚙️ Lightweight & Efficient
Runs in background
Minimal resource usage
🛠️ Tech Stack
Language: Java
Platform: Android
Build System: Gradle (Kotlin DSL)
Core Components:
BroadcastReceiver (SMS Receiver)
SMS Listener Service
Android Activity (UI)
📂 Project Structure
MPTA--Monitoring-and-payment-tracker-application
│
├── app/
│   ├── src/main/java/com/example/testsoundbox3/
│   │   ├── MainActivity.java
│   │   ├── SmsReceiver.java
│   │   └── SmsListener.java
│   │
│   ├── res/layout/
│   │   └── activity_main.xml
│   │
│   └── AndroidManifest.xml
│
├── build.gradle.kts
├── settings.gradle.kts
└── gradle/
⚙️ How It Works
The app uses a BroadcastReceiver to listen for incoming SMS.
When a message arrives:
It is captured by SmsReceiver
Processed by SmsListener
The app analyzes the SMS content to detect:
Payment confirmations
Bank alerts
Relevant transaction data can be stored or displayed.
📥 Installation & Setup
Prerequisites
Android Studio installed
Android device or emulator
Steps
# Clone the repository
git clone https://github.com/your-username/mpta-app.git

# Open in Android Studio
# Build & Run the project
🔐 Permissions Required

The app requires the following permissions:

RECEIVE_SMS
READ_SMS

⚠️ Note: These permissions are sensitive and must be handled carefully as per Android policies.

📌 Use Cases
Personal expense tracking
Monitoring bank SMS alerts
Payment verification systems
Fintech prototype applications
🚧 Future Improvements
📊 Dashboard for transaction visualization
☁️ Cloud sync (Firebase integration)
🔔 Smart notifications
📈 Analytics & reports
🔐 Secure local storage
