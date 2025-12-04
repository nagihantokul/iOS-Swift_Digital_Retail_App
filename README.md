# Digital Retail App

📌 Overview
This project is a digital retail shopping application inspired by luxury brand product catalogs. Built using Swift and SwiftUI, the app follows the MVVM architecture to ensure clean structure, modularity, and scalable code.
Users can browse products, explore categories, view detailed information, add items to Favorites and Cart, and navigate intuitively through the app’s interface. The design emphasizes elegance, clarity, and a smooth user experience.

🎯 Main Features

🛍️ Product Catalog
Dynamically loaded products from a local products.json file
Clean category-based browsing
High-quality product images
Product cards with pricing and quick interactions

❤️ Favorites System
Add or remove products from Favorites
Dedicated Favorites page
Favorite status visually indicated and updated in real-time

🛒 Shopping Cart
Add/remove items from cart
Real-time cart icon badge updates
Total price calculation
Checkout button & order confirmation flow

🔎 Product Detail View
Swipeable gallery using TabView
Product name, description, and price
Add to Favorites & Add to Cart buttons
Recommended items shown from the same category

📂 JSON Data Handling
Each product entry includes:
id
name
price
description
images
category
Products are decoded using a custom Bundle extension.

🏗️ Architecture — MVVM
The app follows the Model–View–ViewModel structure.
Model
Product model
JSON decoding through Bundle.main.decode()
Manages the structure of product data
View
Reusable and organized UI components:
ContentView
HomeView
ProductListView
ProductDetailView
FavoritesView
CartView
CheckoutFormView
OrderConfirmationView
PaymentView
SideMenuView
CategoryCard
ProductCard
ViewModel
Manages product loading
Handles Favorites logic
Handles Cart logic
Supports view updates and ensures separation of concerns

🧰 Technologies Used
Swift 5
SwiftUI
MVVM Architecture
NavigationStack
TabView & PageTabViewStyle
@State, @Binding, @ObservedObject
JSON Decoding

🖼️ App Icon
A custom app icon was designed using Figma, created specifically for this project.

🚀 How to Run
Clone or download the project folder.
Open the project in Xcode 15+.
Run on an iOS Simulator or physical device.
Ensure products.json is included in the app bundle.
