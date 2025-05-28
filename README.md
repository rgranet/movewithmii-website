# MoveWithMii - Official Website

[![Website Status](https://img.shields.io/website?url=https%3A//rubengranet.github.io/movewithmii-website)](https://rubengranet.github.io/movewithmii-website)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

> **Move More, Phone Less** - The first fitness app that blocks your distracting apps until you reach your daily step goal.

## 🎯 About MoveWithMii

MoveWithMii is a unique fitness motivation app that transforms screen time into active time. By temporarily blocking selected distracting apps until users reach their daily step goals, it creates a powerful incentive system for maintaining an active lifestyle.

### Key Features
- **🏃‍♂️ HealthKit Integration**: Seamlessly tracks daily steps and fitness metrics
- **📱 Smart App Blocking**: Uses Apple's Family Controls framework for temporary app restrictions
- **🎯 Self-Controlled Motivation**: Users voluntarily choose which apps to block
- **🔓 Automatic Unlocking**: Apps become available when fitness goals are achieved
- **🛡️ Privacy First**: Zero data collection - everything stays on your device
- **⚡ Daily Reset**: Fresh motivation every day with automatic goal resets

## 🌐 Website Purpose

This website serves as the official presentation platform for MoveWithMii, designed to:

- **📋 Support App Store submission**: Detailed explanation for Apple's review process
- **🔍 Demonstrate legitimate use**: Showcase how Family Controls is used for positive self-improvement
- **🛡️ Highlight privacy commitment**: Emphasize zero data collection approach
- **👥 Provide developer contact**: Clear communication channel for inquiries

## 🏗️ Website Structure

```
movewithmii-website/
├── index.html          # Main website file
├── README.md           # This file
└── assets/            # Future: Screenshots, icons, etc.
```

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#33abdc` - Main brand color
- **Success Green**: `#4dd964` - Achievement and progress
- **Warning Orange**: `#f2b817` - Accent and highlights
- **Text Dark**: `#1a1a1c` - Primary text
- **Text Light**: `#6a6a6c` - Secondary text

### Typography
- **Font Family**: `-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`
- **Design Language**: Modern iOS/Apple design principles
- **Visual Effects**: Glass morphism, gradients, subtle shadows

## 🚀 Development

### Local Development
1. Clone the repository
```bash
git clone https://github.com/[YOUR-USERNAME]/movewithmii-website.git
cd movewithmii-website
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

3. Visit `http://localhost:8000`

### Deployment
The website is automatically deployed via GitHub Pages:
- **Live URL**: `https://[YOUR-USERNAME].github.io/movewithmii-website/`
- **Deployment**: Automatic on push to `main` branch
- **CDN**: Global distribution via GitHub's CDN

## 📱 App Information

### Technical Details
- **Bundle ID**: `com.withmii.movewithmii`
- **Platform**: iOS 17.0+
- **Frameworks**: SwiftUI, HealthKit, Family Controls, SwiftData
- **Privacy**: Zero data collection, local storage only
- **Monetization**: Freemium (Weekly $0.99, Yearly $24.99)

### Development Status
- **Current Phase**: Pre-launch (awaiting Family Controls approval)
- **Target Launch**: Q2 2025
- **Developer**: Ruben Granet

## 🛡️ Privacy & Security

### Data Handling
- **No Data Collection**: Zero personal information gathered
- **Local Storage**: All data remains on user's device
- **Apple Standards**: Follows iOS privacy guidelines
- **User Control**: Complete control over all app restrictions

### Permissions
- **HealthKit**: Read step count, calories, exercise minutes
- **Family Controls**: Temporary app blocking functionality
- **Notifications**: Optional goal reminders and achievements

## 📞 Contact & Support

### Developer Information
- **Name**: Ruben Granet
- **Email**: support@movewithmii.com
- **Response Time**: 24-48 hours

### Links
- **Privacy Policy**: [Privacy Policy](https://[YOUR-USERNAME].github.io/movewithmii-privacy/)
- **Support Page**: [Support](https://[YOUR-USERNAME].github.io/movewithmii-privacy/support.html)
- **Apple Developer**: [Family Controls Request](https://developer.apple.com/contact/request/family-controls-distribution)

## 🎯 Family Controls Usage

### Legitimate Use Case
MoveWithMii uses Apple's Family Controls framework for:
- **Positive self-improvement** (not parental control)
- **Voluntary user restrictions** (user chooses apps to block)
- **Health-based motivation** (encouraging physical activity)
- **Temporary limitations** (automatic unlocking on goal achievement)

### Benefits
- **Increased Physical Activity**: Users walk more to unlock apps
- **Reduced Screen Time**: Natural decrease in device usage
- **Habit Formation**: Daily goal achievement builds healthy routines
- **Digital Wellness**: Better relationship with technology

## 📈 Future Enhancements

### Planned Features
- **AI Fitness Assistant**: Personalized recommendations (coming soon)
- **Advanced Statistics**: Detailed progress analytics
- **Social Features**: Optional goal sharing with friends
- **Apple Watch**: Companion app for better tracking

### Website Improvements
- **Screenshots Gallery**: Visual app demonstration
- **Video Demo**: Interactive app preview
- **Testimonials**: User success stories
- **Blog**: Fitness and digital wellness content

## 📄 License

This website is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Apple**: For providing excellent development frameworks
- **iOS Community**: For inspiration and best practices
- **Health & Fitness Industry**: For promoting active lifestyles

---

**MoveWithMii** - Transforming screen time into active time, one step at a time. 🚶‍♂️

*Built with ❤️ by Ruben Granet*
