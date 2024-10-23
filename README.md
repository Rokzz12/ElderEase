**ElderEase**

ElderEase is a mobile application designed specifically to assist elderly individuals, particularly those suffering from early stages of dementia. The app provides essential tools to improve the quality of life for elderly users by managing their daily tasks, stimulating their mental health through brain games and puzzles, and fostering community support. The intuitive interface is crafted to be user-friendly, ensuring that elderly individuals can navigate it with ease.

Key Features
Brain Games & Puzzles: Designed to stimulate cognitive abilities, these games help keep the mind active and focused.
Community Support: A community chat feature where users can interact, share experiences, and provide each other emotional and mental support.
Pill Reminder: A reliable reminder system to ensure that users take their medications on time.
Doctor Appointment Scheduler: Schedule and manage appointments with doctors easily, complete with reminders and notifications.
SOS Button: A one-click emergency button that can send an alert to predefined contacts with location details in case of an emergency.

Technologies Used
Flutter: Cross-platform framework used for developing the mobile app for both Android and iOS platforms.
OCR API: Optical Character Recognition is used to read prescriptions or labels on medication bottles for ease of pill management.
Firebase: Provides backend services including authentication, real-time database, cloud storage, and push notifications.
BLoC (Business Logic Component): State management pattern used for managing and scaling the app’s complex state logic efficiently.
Cloud Store: Data storage solution used to store user-related data such as appointments, medication schedules, and community messages securely.

Installation
To run the project locally, follow these steps:

Clone the repository:
https://github.com/Rokzz12/ElderEase.git

Install dependencies: Run the following command to install all necessary dependencies:
flutter pub get

Configure Firebase:
Download the google-services.json file from your Firebase project and add it to the android/app directory.
For iOS, download the GoogleService-Info.plist file and add it to your project under the iOS directory.

Run the app: To start the app on an emulator or a physical device, use:
flutter run

**Usage**
Once the app is installed, users can:

Set up their profile and add their medical information, including medications and emergency contacts.
Schedule doctor appointments and receive reminders.
Engage in brain games and puzzles to stimulate cognitive function.
Interact with others in the community section for support.
Use the pill reminder system to manage medications.
In case of emergencies, press the SOS button to notify their emergency contacts.
