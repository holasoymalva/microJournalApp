# MicroJournal

<p align="center">
  <h3 align="center">MicroJournal</h3>
  <p align="center">Capture moments and thoughts throughout your day.</p>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#requirements">Requirements</a> •
  <a href="#installation">Installation</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#license">License</a>
</p>

## Overview

MicroJournal is a minimal journaling app designed exclusively for Apple Watch. It allows users to quickly capture thoughts, ideas, and moments directly from their wrist without requiring their iPhone.

The app focuses on simplicity and speed, letting users jot down short entries in seconds, perfect for those fleeting thoughts or moments of inspiration.

## Features

### Core Features
- ⚡️ **Quick Text Entry** - Capture thoughts in seconds
- 🕐 **Timestamped Entries** - Track when you recorded each thought
- 📋 **Recent Entries View** - Easily browse your latest thoughts
- 🔄 **Context Menu Actions** - Quickly delete or edit entries

### Premium Features
- 😊 **Mood Tracking** - Tag entries with emotional context
- 📊 **Mood Analysis** - View patterns in your emotional state
- ☁️ **iCloud Sync** - Access your journal across devices
- 📤 **Data Export** - Export your entries as JSON

## Requirements

- watchOS 8.0+
- Xcode 13.0+
- Swift 5.5+

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/holasoymalva/microJournalApp.git
   ```

2. Open the project in Xcode
   ```bash
   cd microJournalApp
   open MicroJournal.xcodeproj
   ```

3. Select your Apple Watch device/simulator and run the app

## Architecture

MicroJournal follows the MVVM (Model-View-ViewModel) architecture pattern:

- **Models**: Define the data structure for journal entries
- **ViewModels**: Handle business logic and data operations
- **Views**: Present the user interface using SwiftUI

### Key Components

- `JournalEntry`: Model representing a single journal entry
- `JournalStore`: ViewModel managing entry persistence and retrieval
- `SubscriptionManager`: Handles premium feature access and in-app purchases
- `CloudKitService`: Manages cloud synchronization operations

## Building for Production

1. Update bundle identifier in project settings
2. Configure your App Store Connect account
3. Create app record in App Store Connect
4. Configure in-app purchases for premium subscription
5. Archive and upload to App Store Connect

## Screenshots

<p align="center">
  <img src="Screenshots/main-view.png" width="230">
  <img src="Screenshots/new-entry.png" width="230">
  <img src="Screenshots/mood-analysis.png" width="230">
</p>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- SwiftUI for the elegant UI framework
- CloudKit for seamless cloud synchronization
- The Apple Developer documentation team for comprehensive guides
