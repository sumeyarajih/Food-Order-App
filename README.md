🍔 Overview

OrderUp simplifies online food ordering by connecting users with restaurants in their area.
It provides real-time order tracking, secure payments, and a seamless user experience across both Android and iOS.

🚀 Key Features

✅ Browse Restaurants – View available restaurants with images and ratings.
✅ Menu & Categories – Explore detailed menus by category (Burgers, Drinks, Desserts, etc.).
✅ Add to Cart – Select and customize food items (size, extras, quantity).
✅ Order Tracking – Track your order status in real time.
✅ User Authentication – Login, signup, and profile management.
✅ Search & Filter – Quickly find your favorite dishes.
✅ Dark Mode Support (optional)
✅ Secure Payment Integration (to be implemented later)

🧱 Project Structure
OrderUp/
 ┣ android/                 # Native Android project
 ┣ ios/                     # Native iOS project
 ┣ src/
 ┃ ┣ assets/                # Images, icons, fonts
 ┃ ┣ components/            # Reusable UI components (buttons, cards, etc.)
 ┃ ┣ navigation/            # App navigation (React Navigation setup)
 ┃ ┣ screens/               # App screens (Home, Cart, Profile, etc.)
 ┃ ┣ services/              # API calls & backend communication
 ┃ ┗ utils/                 # Helper functions, constants
 ┣ App.tsx                  # Root component
 ┣ package.json             # Dependencies & scripts
 ┣ babel.config.js          # Babel configuration
 ┣ metro.config.js          # Metro bundler config
 ┣ tsconfig.json            # TypeScript configuration
 ┗ README.md                # Project documentation

⚙️ Tech Stack

Frontend: React Native (TypeScript)

State Management: React Hooks / Context API (or Redux)

Backend: Next.js API (or Node.js + Express)

Database:  PostgreSQL

Payment: Chapa or arif pay

Authentication: Firebase Auth or JWT-based login

🪄 Setup & Installation

Clone the repository

git clone https://github.com/yourusername/OrderUp.git
cd OrderUp


Install dependencies

npm install
# or
yarn install


Run Metro Bundler

npx react-native start


Run the app

npx react-native run-android
# or
npx react-native run-ios

🔗 Backend Setup (Next.js Example)

Your backend API (e.g., /backend folder) handles:

User registration & login

Restaurant and menu data

Order processing & tracking

Payment integration

You can create a Next.js backend separately using:

npx create-next-app@latest backend

💡 Future Improvements

Push notifications for order updates

Live chat with restaurants

Real-time delivery tracking on map

Loyalty points and discounts system

Admin dashboard for restaurant owners

👩‍💻 Developer

Sumeya Rajih
📍 Dire Dawa University – Software Engineering
📧 sumeyarajih@gmail.com
