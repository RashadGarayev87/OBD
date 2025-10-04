CarE - OBD-II Car Dashboard
###Installation 

# 📥 

| Version | File | Download link |
|---------|----------|---------------|
| -----------------------------------------------------------------------------------------------|
| v2.0    | CarE_v2.0.apk | [Download](https://github.com/RashadGarayev87/OBD/releases/tag/v2.0) |
| v3.0    | CarE_v3.0.apk | [Download](https://github.com/RashadGarayev87/OBD/releases/download/v3.0/CarE_v3.0.apk) |



A comprehensive Android OBD-II dashboard application for real-time vehicle monitoring and diagnostics, specifically optimized for Kia Sorento 2003 models.
🚗 Features
📊 Real-time Dashboard

    Analog Gauges: Beautiful RPM and Speed gauges with gear position display

    Live Sensor Data: Coolant temperature, engine load, MAF rate, fuel levels

    Trip Monitoring: Dual trip tracking (Trip A & Trip B) with fuel consumption

    Gear Position: Automatic gear detection based on RPM and speed

🔧 Diagnostics

    Error Code Reading: Read and clear DTC (Diagnostic Trouble Codes)

    Comprehensive Sensor Data: 25+ different sensor readings

    Real-time Monitoring: Continuous vehicle parameter monitoring

📈 Statistics & Analytics

    Fuel Consumption Tracking: Instant and average fuel consumption

    Distance Tracking: Trip distance and total distance monitoring

    Graphical Analysis: Fuel consumption and distance charts

    Data Export: CSV export capability for further analysis

🌐 Multi-language Support

    Azerbaijani (Default)

    Russian

    English

📱 Multi-screen Support

Optimized for various screen sizes:

    6.2" (800x480)

    7.0" HD (1280x720)

    7.0" Standard (1024x600)

    8.0" HD (1280x720)

    9.0" Standard (1024x600)

    9.0" HD (1280x720)

    10.1" HD (1280x720)

🛠 Technical Specifications
Supported Protocols

    ISO 14230-4 KWP (5 baud init)

    ISO 14230-4 KWP (fast init)

    ISO 9141-2

    AUTO - Automatic protocol detection

Sensor Support

    Engine RPM & Vehicle Speed

    Coolant Temperature & Engine Load

    MAF (Mass Air Flow) Rate

    Fuel Pressure & Fuel Level

    Throttle Position & Timing Advance

    Intake/Ambient Temperature

    Oxygen Sensor & Barometric Pressure

    Voltage & Engine Runtime

    Distance Tracking

    And many more...

📋 Requirements
Hardware

    Android device 5.0+ (API 21+)

    OBD-II ELM327 WiFi adapter only

    Compatible vehicle (Kia Sorento 2003 optimized)

Software

    Android 5.0 or higher

    WiFi  connectivity

    OBD-II port access

🔌 Installation
APK Installation

    Download CarE_v1.0.apk from releases

    Enable "Install from unknown sources" in Android settings

    Install the APK file

    Launch CarE application

OBD-II Setup

    Connect your ELM327 adapter to vehicle's OBD-II port

     connect to WiFi OBD

    Launch CarE app

    Select your preferred language and screen size

    The app will automatically detect and connect to your OBD-II adapter

🎮 Usage
Main Dashboard

    Top Section: Analog RPM and Speed gauges with gear indicator

    Middle Section: Real-time sensor data and trip information

    Bottom Section: Warning messages and status indicators

Navigation Tabs

    Dashboard - Main driving interface

    Statistics - Fuel consumption and distance analytics

    Error Codes - Diagnostic trouble codes reading and clearing

    Sensors - Comprehensive sensor data list

    About - Application information and credits

Trip Management

    Trip A: Current journey (resettable)

    Trip B: Total accumulated data

    Fuel Tracking: Real-time consumption calculation

    Distance: Accurate trip distance measurement

🔧 Technical Details
Architecture

    Frontend: Kivy/KivyMD for cross-platform UI

    Backend: Python 3.8 with socket communication

    Database: SQLite for data persistence

    Charts: Matplotlib for data visualization

OBD-II Implementation

    Direct socket communication with ELM327

    Multi-protocol support with automatic detection

    Thread-safe data reading and processing

    Real-time sensor data processing

Data Storage

    SQLite database for trip data persistence

    Automatic data saving every 10 seconds

    Export functionality to CSV format

    Internal and external storage support

🐛 Known Issues & Limitations
Current Version (v1.0)

    Optimized specifically for Kia Sorento 2007

    Some sensors may not be available on all vehicles

    WiFi OBD adapters recommended for stability

    Requires stable connection for best performance

Compatibility

    Best results with ELM327(clone include) v1.5+ adapters

    WiFi adapters provide more stable connection

    Some vehicles may require protocol manual selection

🔄 Future Updates
Planned Features (v1.1)

    Additional vehicle profiles

    Enhanced error code descriptions

    Data logging and history

    Customizable dashboard layouts

    More language support

    Advanced diagnostics

Technical Improvements

    WIFI support

    Background data collection

    Cloud synchronization

    Extended vehicle compatibility

📊 Performance
Memory Usage

    Average RAM: ~150-200MB

    Storage: ~50MB (including data)

    Battery: Moderate (continuous OBD communication)

Connection Stability

    Auto-reconnection on disconnect

    Connection status monitoring

    Error handling and recovery

🤝 Contributing

We welcome contributions to improve CarE:

    Fork the repository

    Create a feature branch

    Make your changes

    Test thoroughly

    Submit a pull request

Areas for Contribution

    Additional vehicle compatibility

    New sensor implementations

    UI/UX improvements

    Translation additions

    Performance optimizations

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
👨‍💻 Developer

Rashad Garayev

    Email: garayevrashad@hotmail.com

    GitHub: https://github.com/RashadGarayev87

    Specialization: Automotive diagnostics and car monitor applications

🙏 Acknowledgments

    Kivy/KivyMD community for excellent cross-platform framework

    Python OBD library contributors

    ELM327 protocol documentation

    Beta testers and contributors

📞 Support

For technical support or feature requests:

    Check the GitHub issues page

    Create a new issue with detailed description

    Include your vehicle model and OBD adapter type

    Provide log files if possible

🔗 Links

    GitHub Repository

    Download APK

    Documentation

    Issue Tracker

Note: This application is designed for educational and informational purposes. Always follow safe driving practices and consult professional mechanics for vehicle repairs and diagnostics.

Version: 1.0 Beta
Last Updated: December 2024
Compatibility: Android 5.0+ (API 21+)
# OBD
