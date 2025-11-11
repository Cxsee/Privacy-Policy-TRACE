**Privacy Policy for TRACE Dashboard**
This is an open source Android app developed for agricultural monitoring.

As a developer who values user privacy, I take data protection very seriously.

**Data collected by the app**
I hereby state, to the best of my knowledge and belief, that this app collects and processes the following data:

**Data stored locally on your device:**
App preferences: Theme settings, language preferences, and display configurations are stored locally on your device
Authentication tokens: JWT tokens for secure communication with the backend server are stored locally using secure storage

ìThis local data can be completely erased by clearing the app's data or uninstalling the application.

**Data sent to and stored on our servers:**
User account information: Name, surname, email address (required for registration and consortium management)
Sensor associations: Which sensors are assigned to your account
Irrigation notes: Manual irrigation records you create (date, quantity, notes)
Threshold configurations: Alarm settings you configure for sensor monitoring
Device tokens: Firebase Cloud Messaging (FCM) tokens to send you push notifications when sensor thresholds are exceeded
Important: Sensor measurement data (temperature, humidity, soil moisture, etc.) is collected by IoT devices and stored in our InfluxDB time-series database. This data is used solely for agricultural monitoring purposes and is accessible only to authorized users within your consortium.

**How we use your data**
Authentication: Email and password (hashed with BCrypt) are used to authenticate your access to the system
Notifications: FCM device tokens are used exclusively to send you alerts when your configured sensor thresholds are exceeded
Data visualization: Sensor data is displayed in charts and tables within the app
Consortium management: Your information is shared only with administrators of your consortium for sensor assignment and management purposes

**Data sharing**
Your data is NOT sold to third parties
Your data is NOT used for advertising or marketing purposes
Sensor data is accessible only to:
You (the user)
Administrators of your consortium
Admin (for system management purposes only)

**Third-party services**
This app uses the following third-party services:

Firebase Cloud Messaging (FCM): For push notifications. Subject to Google's Privacy Policy
Backend server: For data storage and processing

**Explanation of permissions requested in the app**

android.permission.INTERNET	Required to communicate with the backend server to fetch sensor data and send user commands. Essential for the app to function.
android.permission.POST_NOTIFICATIONS	Required to show push notifications when sensor thresholds are exceeded. Can be revoked by the user at any time, but you will not receive threshold alerts.
android.permission.WAKE_LOCK	Allows the app to keep the device awake when processing critical notifications or data updates. Automatically granted by the system.
android.permission.ACCESS_NETWORK_STATE	Checks if the device is connected to the internet before attempting data synchronization. Automatically granted by the system.

**Your rights**
You have the right to:

Delete your account and all associated data by contacting the system administrator
Revoke notification permissions at any time through Android settings
Export your irrigation notes and threshold configurations (contact administrator)

**Data retention**
User account data is retained as long as your account is active
Authentication tokens expire after 1 hour (access token) or 7 days (refresh token)

**Security**
All communication with the backend server uses HTTPS encryption (in production)
Passwords are hashed using BCrypt before storage
Authentication uses JWT tokens with expiration
Database access is restricted and requires authentication

**Changes to this policy**
This privacy policy may be updated from time to time. Users will be notified of significant changes through app updates.




Last updated: November 11, 2025

