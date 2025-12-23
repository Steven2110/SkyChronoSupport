# SkyChrono — Real-time Astronomical Data

SkyChrono is a comprehensive astronomical companion app that provides precise, real-time information about celestial events, sun and moon positions, twilight periods, and multiple time systems used in astronomy and navigation.

Whether you’re planning a stargazing session, timing golden hour for a shoot, or studying celestial mechanics, SkyChrono gives you the sky data you need—fast and accurately.

---

## Key Features

### 🌞 Sun Tracking
- Real-time altitude and azimuth
- Sunrise, sunset, and solar noon times
- Civil, nautical, and astronomical twilight periods
- Current lighting conditions (daylight / twilight / night)
- Day length calculations

### 🌙 Moon Information
- Moon phase with illumination percentage
- Moonrise and moonset times
- Real-time position tracking (alt/az)
- Phase progression visualization

### ⏰ Multiple Time Systems
- Local time with timezone
- UTC
- Julian Date (JD)
- Modified Julian Date (MJD)
- Greenwich Mean Sidereal Time (GMST)
- Local Sidereal Time (LST)

### 📍 Flexible Location Options
- Automatic GPS-based positioning (optional)
- Manual coordinate input anywhere worldwide
- Decimal degrees and DMS (Degrees/Minutes/Seconds) formats

### 🔔 Smart Notifications (Optional)
- Sunrise and sunset alerts
- Moon phase notifications (new/full/quarters)
- Golden hour and blue hour reminders
- Twilight boundary alerts (civil/nautical/astronomical)
- Customizable timing

### 🌃 Night Vision Mode
- Red-tinted theme to preserve night vision
- Ideal for observatories and dark-sky locations
- Quick and seamless switching

### 📊 Data Export
- Save the dashboard as a high-resolution image
- Export data as JSON for integration with other tools
- Copy individual values with a tap

### 🎓 Educational Resources
- Built-in explanations for astronomy concepts
- Quick learning on coordinate systems, twilight, and time standards
- Helpful for students and beginners

### ♿ Accessibility
- VoiceOver support
- Accessibility labels across key UI components

---

## Technical Details

### Requirements
- iOS 18.0 or later
- Location services (optional, for automatic positioning)
- Notification permissions (optional, for alerts)

### Frameworks Used
- SwiftUI
- CoreLocation
- TipKit
- UserNotifications
- Combine

### Architecture
- MVVM (Model–View–ViewModel)
- Observable macro for state management
- Coordinator pattern for navigation
- Service-based design for location/time/notification logic

### Key Components
- **TimeService**: JD/MJD/UTC/GMST/LST conversions and formatting
- **LocationService**: GPS + manual coordinate input
- **NotificationService**: Scheduling and managing alerts
- **SunCalculator**: Sun position and event calculations
- **MoonCalculator**: Moon position, phase, and event calculations

---

## About the Developer

**Hi 👋, I'm Steven Wijaya.**

I build iOS apps that turn complex ideas into practical tools. SkyChrono was created to make astronomical time systems and sky-position data easy to access in real time—without ads, tracking, or subscriptions.

---

## Connect with the Developer
- **Instagram:** [steven_wijaya249](https://www.instagram.com/steven_wijaya249/)
- **LinkedIn:** [stevenwijaya2110](https://www.linkedin.com/in/stevenwijaya2110/)
- **Email:** [steven.wijaya2001@gmail.com](mailto:steven.wijaya2001@gmail.com?subject=SkyChrono%20Support)

---

## Privacy Policy
SkyChrono does not track you and does not send your data to external servers. For details, see: **[PrivacyPolicy.md](PrivacyPolicy.md)**

---

## License
Copyright © 2025 Steven Wijaya. All rights reserved.

---

*SkyChrono — Your window to the cosmos.*
