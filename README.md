# Retail Store E-Commerce Flutter App UI

A modern and elegant Flutter UI for a grocery/retail store e-commerce mobile application. This project showcases a complete user interface for an online grocery shopping experience with clean design and intuitive navigation.

## Features

### User Authentication
- **Sign In Screen** - Login with email and password
- **Sign Up Screen** - Create new account with name, email, and password
- **Password Visibility Toggle** - Show/hide password functionality

### Shopping Experience
- **Home Screen** - Featured promotional banner and popular deals
- **Categories** - Browse products by categories:
  - Fruits
  - Vegetables
  - Meat
  - Fish
  - Sea Food
  - Juice
  - Egg & Milk
  - Ice Cream
  - Cake
  - Bottle
  - Cleaner
- **Product Cards** - Display products with images and prices

### Cart & Orders
- **Shopping Cart** - Add/remove items with quantity control
- **Order History** - View past orders with status (Delivered, Canceled)
- **Order Details** - View order information and dates
- **Checkout** - Complete purchase flow

### User Profile
- **Profile Settings** - Manage account information
- **Edit Profile** - Update user details
- **Change Password** - Secure password change
- **My Cards** - Manage payment methods
- **Notifications Toggle** - Enable/disable notifications
- **Language Settings** - Change app language
- **Logout** - Sign out functionality

## Result

### 📱 Screenshots

<table>
  <tr>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/SplashScreen.jpeg" width="250"/></td>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/WelcomeScreen.jpeg" width="250"/></td>
  </tr>
  <tr>
    <td align="center">Splash Screen</td>
    <td align="center">Welcome Screen</td>
  </tr>
  <tr>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/HomeScreen.jpeg" width="250"/></td>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/CategoriesScreen.jpeg" width="250"/></td>
  </tr>
  <tr>
    <td align="center">Sign In</td>
    <td align="center">Sign Up</td>
  </tr>
  <tr>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/CartScreen.jpeg" width="250"/></td>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/OrdersScreen.jpeg" width="250"/></td>
  </tr>
  <tr>
    <td align="center">Home Screen</td>
    <td align="center">Categories</td>
  </tr>
  <tr>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/LoginScreen.jpeg" width="250"/></td>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/SignUpScreen.jpeg" width="250"/></td>
  </tr>
  <tr>
    <td align="center">Shopping Cart</td>
    <td align="center">Orders</td>
  </tr>
  <tr>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/ProfileWhenNotifcationsOn.jpeg" width="250"/></td>
    <td><img src="https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI/blob/main/result/screenshots/ProfileWhenNotifcationsOff.jpeg" width="250"/></td>
  </tr>
  <tr>
    <td align="center">Profile</td>
    <td align="center">Profile with Notifications Off</td>
  </tr>
</table>

### Video

https://github.com/user-attachments/assets/20b39b2d-e3f1-4a82-b058-0d963bbbcb17

## 🎨 Design Features

- **Color Scheme**: Orange (#FF6B00) and Brown accents
- **Modern UI**: Clean and minimalist design
- **Smooth Navigation**: Bottom navigation bar with 5 tabs (Home, Items, Cart, Orders, Account)
- **Custom Icons**: Category-specific icons with colored backgrounds

## 🛠️ Technologies Used

- **Flutter** - UI framework
- **Dart** - Programming language
- **Material Design** - Design system

## 📂 Project Structure

```
lib/
├── core/
│   └── resources/
│       ├── app_colors.dart
│       ├── app_field.dart
│       └── app_images.dart
├── features/
│   ├── home_nav/
│   │   ├── screens/
│   │   │   ├── cart/
│   │   │   ├── categories/
│   │   │   ├── home/
│   │   │   ├── orders/
│   │   │   └── profile/
│   │   └── view.dart
│   ├── login/
│   ├── signup/
│   ├── splash/
│   ├── welcome/
│   └── widgets/
│       ├── cart_item.dart
│       ├── category_item.dart
│       ├── counter.dart
│       ├── custom_password_field.dart
│       ├── deal_item.dart
│       ├── order_item.dart
│       ├── profile_item.dart
│       └── switch.dart
└── main.dart
```

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.0.0 or higher)
- Dart SDK (3.0.0 or higher)
- Android Studio / VS Code with Flutter extensions
- Android Emulator or iOS Simulator

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MostafaEdrees11/Retail_Store_E_commerce_Flutter_App_UI.git
   ```

2. **Navigate to project directory**
   ```bash
   cd Retail_Store_E_commerce_Flutter_App_UI
   ```

3. **Install dependencies**
   ```bash
   flutter pub get
   ```

4. **Run the app**
   ```bash
   flutter run
   ```

## 📱 Screens Overview

| Screen | Description |
|--------|-------------|
| **Splash Screen** | App logo and branding |
| **Welcome Screen** | Onboarding with app introduction |
| **Sign In** | User authentication |
| **Sign Up** | New user registration |
| **Home** | Featured deals and categories |
| **Categories** | Browse all product categories |
| **Cart** | Shopping cart with quantity management |
| **Orders** | Order history with ongoing and past orders |
| **Profile** | User settings and preferences |

## 🎯 Key Highlights

- ✅ **UI Only**: This is a UI implementation project without backend integration
- ✅ **Clean Code**: Well-organized and maintainable code structure
- ✅ **Reusable Widgets**: Custom widgets for consistent design
- ✅ **Navigation**: Smooth transition between screens
- ✅ **Responsive**: Works on various screen sizes

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 👤 Author

**Mostafa Edrees**

- GitHub: [@MostafaEdrees11](https://github.com/MostafaEdrees11)

## ⭐ Show your support

Give a ⭐️ if you like this project!

## 📝 Notes

- This is a UI-only project created for learning and demonstration purposes
- Assets and images are for educational use
- No backend or API integration is included in this version

---

**Made with ❤️ using Flutter**