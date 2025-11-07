# Pravasa 🚌 📱

**Smart Travel Data Collection for Better Kerala Transportation**

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)](https://flutter.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kerala](https://img.shields.io/badge/Made%20for-Kerala-green)](https://www.kerala.gov.in)

> *Pravasa* (പ്രവാസ) means "journey" in Malayalam - helping NATPAC understand how Kerala travels.

## 🌟 What is Pravasa?

Pravasa is a privacy-first mobile app that automatically tracks your travel patterns to help improve Kerala's transportation infrastructure. Developed for NATPAC (National Transportation Planning and Research Centre), it replaces expensive manual surveys with smart, automated data collection.

**Your journeys → Better buses, roads & planning for Kerala** 🏞️

## ✨ Key Features

### 🤖 Smart Trip Detection
- **Automatic tracking** - No need to start/stop manually
- **Transport mode recognition** - Bus, car, walk, bike, train, auto-rickshaw
- **Battery optimized** - Uses less than 5% battery per day
- **Offline capable** - Works without internet, syncs later

### 🛡️ Privacy First
- **Anonymous data** - No personal information stored
- **You control everything** - Choose what to share and when
- **Local storage** - Your data stays on device until you choose to share
- **Easy opt-out** - Delete your data anytime

### 🌏 Made for Kerala
- **Malayalam support** - Full app available in Malayalam
- **Local transport modes** - Recognizes KSRTC buses, boats, auto-rickshaws
- **Kerala geography** - Optimized for local routes and landmarks

### 📊 Personal Insights
- **Travel patterns** - See your weekly/monthly travel summary
- **Environmental impact** - Track your carbon footprint
- **Community contribution** - See how your data helps Kerala

## 🚀 Getting Started

### For Users

#### Installation
1. Download from [Google Play Store](#) or [Apple App Store](#)
2. Grant location permissions for trip tracking
3. Complete quick onboarding (2 minutes)
4. Start traveling - the app does the rest!

#### First Steps
1. **Set up privacy preferences** - Choose what data to share
2. **Take a test trip** - Walk around the block to see how it works
3. **Review and verify** - Check if the app detected your trip correctly
4. **Contribute to Kerala** - Your anonymous data helps improve transportation

### For Developers

#### Prerequisites
- Flutter 3.16+ 
- Dart 3.0+
- Android Studio / VS Code
- Device with GPS capability

#### Installation
```bash
# Clone the repository
git clone https://github.com/natpac-kerala/pravaasa.git
cd pravaasa

# Install dependencies
flutter pub get

# Run the app
flutter run
```

#### Project Structure
```
lib/
├── core/           # Core utilities and constants
├── data/           # Data layer (APIs, local storage)
├── domain/         # Business logic and entities
├── presentation/   # UI screens and widgets
├── services/       # Background services (GPS, ML)
└── main.dart       # App entry point
```

## 📱 How It Works

### For Users
1. **Install & Setup** → Grant permissions, set preferences
2. **Travel Normally** → App automatically detects your trips
3. **Quick Review** → Verify/edit detected trips (optional)
4. **Data Contribution** → Anonymous data helps NATPAC plan better transport

### Technical Flow
```
GPS Tracking → Mode Detection → Local Storage → 
User Verification → Data Sync → NATPAC Analytics → 
Better Transportation Planning
```

## 🛠️ Technical Stack

- **Frontend**: Flutter (Cross-platform)
- **Backend**: PostgreSQL + PostGIS
- **Maps**: Google Maps API
- **ML**: TensorFlow Lite (on-device)
- **Storage**: SQLite (local) + Cloud sync
- **Privacy**: AES-256 encryption

## 🤝 Contributing

We welcome contributions from the Kerala tech community!

### Ways to Contribute
- 🐛 **Report bugs** - Help us fix issues
- 💡 **Suggest features** - Ideas for better Kerala transport
- 🌐 **Improve translations** - Better Malayalam localization  
- 📝 **Documentation** - Help others understand the project
- 💻 **Code contributions** - Submit pull requests

### Development Setup
1. Fork the repository
2. Create feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📊 Impact & Results

### Current Status
- 📱 **MVP Phase** - Core features implemented
- 👥 **Target Users** - 50,000 active users in Year 1
- 🎯 **Data Goal** - 1M trips recorded annually
- 🌍 **Coverage** - All 14 districts of Kerala

### How Your Data Helps
- **Better Bus Routes** - Optimize KSRTC routes based on actual demand
- **Road Planning** - Identify where new roads are needed most  
- **Traffic Management** - Understand congestion patterns
- **Public Policy** - Evidence-based transportation decisions

## 🛡️ Privacy & Security

### What We Collect
- ✅ Trip start/end locations (coordinates only)
- ✅ Transportation modes used
- ✅ Trip timing and duration
- ✅ General demographics (age group, region - optional)

### What We DON'T Collect
- ❌ Your name or personal identity
- ❌ Exact addresses or specific locations
- ❌ Photos or personal files
- ❌ Contacts or messages

### Your Rights
- **View your data** - See everything we have
- **Control sharing** - Turn tracking on/off anytime
- **Delete data** - Request complete removal
- **Export data** - Get a copy of your travel data

## 📞 Support & Contact

### For Users
- 📧 **Email**: support@pravaasa.kerala.gov.in
- 🌐 **Website**: [www.natpac.kerala.gov.in/pravaasa](https://www.natpac.kerala.gov.in)
- 📱 **In-app support** - Settings → Help & Support

### For Developers
- 🐛 **Issues**: [GitHub Issues](https://github.com/natpac-kerala/pravaasa/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/natpac-kerala/pravaasa/discussions)
- 📧 **Email**: developers@pravaasa.kerala.gov.in

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **NATPAC Kerala** - Project vision and funding
- **KSCSTE** - Research and development support
- **Kerala Government** - Policy support and infrastructure
- **Flutter Community** - Amazing framework and resources
- **Contributors** - Everyone who helps make Kerala's transport better

## 🗺️ Roadmap

### Phase 1 - MVP (Current)
- [x] Basic trip detection
- [x] Manual trip entry
- [x] Privacy controls
- [x] Malayalam localization

### Phase 2 - Enhanced
- [ ] Advanced ML for better mode detection
- [ ] Real-time traffic integration
- [ ] Community features
- [ ] Gamification elements

### Phase 3 - Scale
- [ ] Integration with KSRTC systems
- [ ] Predictive analytics
- [ ] Other state partnerships
- [ ] Smart city integrations

---

**Made with ❤️ for Kerala by the tech community**

*Pravaasa - Making every journey count for better transportation* 🌴
