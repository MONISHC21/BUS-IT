# BUSit - Bus Transportation App 🚍

A modern Flutter-based cross-platform app for bus route search, live tracking, booking, and voice-assisted navigation.

[![Flutter](https://flutter.dev/images/flutter-logo-sharing.png)](https://flutter.dev) [![GitHub Pages](https://github.com/MONISHC21/BUS-IT/actions/workflows/pages/pages-build-deployment/badge.svg)](https://monishc21.github.io/BUS-IT/)

## 🌐 Live Demo
[Live Web App](https://monishc21.github.io/BUS-IT/)

## 📱 Features
- **Route Search** - Find buses by origin/destination with filters
- **Live Bus Map** - Real-time tracking with Google Maps
- **Bus Details** - Capacity, timeline, route info
- **Voice Assistant** - Natural language queries
- **Login** - Biometric, social, credential login
- **Settings** - Language, notifications, profile
- **Responsive** - Works on mobile, web, desktop

## 🔐 Login Credentials (Demo)
```
Email: commuter@busit.com |

Password: commuter123 (Daily Commuter)

Email: tourist@busit.com |

Password: tourist123 (Tourist)

Email: senior@busit.com |

Password: senior123 (Senior Citizen)

Phone: +919876543210 | Password: mobile123 (Mobile User)

Phone: +919123456789 | Password: driver123 (Bus Driver)
Or use Biometric/Social login (demo mode)
```

## 🛠️ Quick Start (Local)

### Prerequisites
- Flutter SDK >=3.5.0
- Dart SDK
- Android Studio/VS Code

### Setup
```bash
git clone https://github.com/MONISHC21/BUS-IT.git
cd BUS-IT
flutter pub get
flutter run
```

## 📦 Deployment to GitHub Pages (Production Web)
```bash
flutter build web --release --base-href "/BUS-IT/"
mkdir docs
xcopy /E /I /Y build\\web\\* docs\\
git add . && git commit -m "Deploy update" && git push
```
*GitHub Pages auto-deploys from main:/docs*

## 📁 Project Structure
```
lib/
├── presentation/     # Screens: login, route_search, live_bus_map, bus_details, voice_assistant, settings
├── routes/           # App navigation
├── theme/            # Light/Dark themes
├── widgets/          # Custom UI components
└── main.dart         # Entry point
assets/               # Images, SVG
docs/                 # GitHub Pages web build
```

## 🚀 Run on Different Platforms
```bash
# Web (local)
flutter run -d chrome

# Android
flutter run -d android

# iOS
flutter run -d ios

# Windows
flutter run -d windows
```

## 📚 Key Dependencies
- `google_maps_flutter` - Live maps
- `geolocator`, `record` - Location & voice
- `sizer` - Responsive UI
- `dio` - API calls
- Full list: `pubspec.yaml`

## 🔧 Customization
- **Add routes**: Edit `lib/routes/app_routes.dart`
- **Theme**: `lib/theme/app_theme.dart`
- **Assets**: `assets/images/`

## ⚠️ Notes
- Web uses CanvasKit renderer (included)
- Voice/location permissions handled with `kIsWeb` checks
- Demo login for testing; replace with real backend in production

## 🙌 Acknowledgments
- Built with Flutter & Material Design
- Google Maps Flutter plugin
- Sizer for responsive layouts

**License:** MIT

Thankyou ❤️
