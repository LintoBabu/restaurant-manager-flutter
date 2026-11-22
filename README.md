# 🍽️ Restaurant Manager (Flutter)

An offline-first Flutter app for running a small restaurant or mess: take orders at the
counter, manage meal subscriptions, track invoices and keep a customer list. It all runs
on the device with no server.

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-sqflite-003B57?logo=sqlite&logoColor=white)
![Provider](https://img.shields.io/badge/State-Provider-blue)

## ✨ Features

- **Point of sale:** browse the menu by category (breakfast, lunch, dinner, snacks, juices, desserts), add items to a cart, and check out to a payment and success screen.
- **Mess subscriptions:** add members, see today's mess list, and track pending, completed and validity periods.
- **Invoices:** separate pending and completed invoices, each with a detail view.
- **Customers and delivery:** a customer list, new-customer form and delivery page.
- **Offline storage:** the cart is saved locally in SQLite (`sqflite`), with app state handled by `provider`.

## 🧱 Structure

```
lib/
├─ pages/      sales & cart, food categories, mess, invoices, customers, delivery, login
├─ Provider/   cart state (ChangeNotifier)
├─ Model/      cart model
├─ db/         SQLite helper
└─ widgets/    shared item and cart widgets
```

## 🚀 Run locally

```
flutter pub get
flutter run
```
