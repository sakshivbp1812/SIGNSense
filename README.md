# SIGNSense: Bridging Worlds

## Purpose:

SIGNSense is a groundbreaking application designed to bridge the communication gap between deaf and non-deaf individuals. By leveraging cutting-edge technology, it provides an intuitive interface where users can seamlessly understand sign language through a graphical context. Whether you're deaf or non-deaf, SIGNSense offers a platform for inclusive communication and understanding.

## Usage & Current Functionality:

Using SIGNSense is effortless. Simply point your device's camera towards the sign language speaker, and watch as the application instantly converts the signs into text in real-time. This mobile application empowers users to translate sign language anytime, anywhere, fostering greater accessibility and inclusivity.

### Home Page

Upon launching SIGNSense, users are greeted with a user-friendly home page offering three options: Login, Register, or Continue as Guest. Authentication allows users to save and access their translation history seamlessly.

### Login and Register

Registering an account is straightforward—users can sign up using their email and password, creating a unique profile. Upon logging in, the app generates a unique user ID for personalized access to backend features and translation history.

### Camera Page

The heart of SIGNSense lies in its camera page, where users can record and convert sign language into readable text in real-time. The interface provides visual feedback, adjusting color and providing helpful prompts like "Keep Steady for accurate results" based on the confidence score of translations.

### Settings Page

Customization is key in SIGNSense. Users can tailor their experience by adjusting theme, color, and font-size preferences. Additionally, they can manage login/logout actions conveniently from the settings menu.

### Install dependencies and run on your local machine

To deploy SIGNSense locally, ensure you have emulators, Flutter, and Python installed on your machine. Follow these simple steps:

Clone the SIGNSense project repository onto your local machine:

```bash=1
git clone https://github.com/sakshivbp1812/SIGNSense
```

Install all the python packages and start backend server. Go into the backend folder and install all pip packages:

```bash=2
cd backend
pip install -r requirements.txt
cd ../
```

To install all the Flutter dependencies and run the flutter application:

```bash=7
cd frontend
flutter pub get
flutter run
```

The application runs on Andriod/iOS emulator on your local machine. The server runs on **localhost:5000** on your local machine.
