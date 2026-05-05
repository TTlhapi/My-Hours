# My-Hours
Time tracking application 

This is an Android application for time tracking . It demonstrates navigation, login functionality, and a main activity with a launcher intent. The app uses a modern Android theme and supports backup and restore features.

📂 Project Structure
AndroidManifest.xml  
Defines application metadata, activities, permissions, and backup rules.

Activities:

MainActivity: Entry point of the app, launched when the application starts.

login: Handles user authentication.

NavigationDrawer: Provides navigation UI with a drawer layout.

⚙️ Configuration
Application Settings
Backup & Restore:
Configured with data_extraction_rules and backup_rules for secure data handling.

Theme:
Uses Theme.OPSC7311_PROTOTYPEapp with support for RTL layouts.

Icon & Label:
Defined in @mipmap/ic_launcher and @string/app_name.

Activity Export Rules
MainActivity: Exported (true) to allow launching from the system.

login and NavigationDrawer: Not exported (false) for internal use only.

🚀 Getting Started
Prerequisites
Android Studio (latest version recommended)

Android SDK 31 or higher

Emulator or physical device running Android 12 (API level 31) or above

Setup Instructions
Clone the repository:

bash
git clone https://github.com/your-repo/opsc7311-prototype.git
cd opsc7311-prototype
Open the project in Android Studio.

Build and run the app:

Select an emulator or connected device.

Click Run ▶️.

🛠️ Features
Login Screen for user authentication

Navigation Drawer for structured app navigation

Main Activity as the app’s entry point

Backup & Restore support for user data

Modern Theme with RTL support

📌 Notes
Ensure your development environment targets API level 31 or higher.

Activities marked as exported="false" are restricted to internal app use for security.

Customize @string/app_name and @mipmap/ic_launcher for branding.
