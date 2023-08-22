# CuisineConnect

CuisineConnect is a social platform that connects students who want to share and enjoy homemade food. This platform allows student chefs to showcase their culinary skills and menu offerings, while fellow students can discover, order, and enjoy delicious homemade meals.

## Features

- Browse diverse homemade cuisine options.
- View detailed menus, including dishes, prices, and dietary information.
- Contact student chefs for personalized orders or inquiries.
- Easy signup and profile creation for both chefs and food enthusiasts.
- Ratings and reviews to ensure quality and trust within the community.

## Project Structure

- `CuisineConnect`: Main folder containing the core components of the app.
  - `CuisineConnectApp.swift`: Entry point for the SwiftUI app instance.
  - `ContentView.swift`: Main UI where users can browse cuisine options and interact with the app.
  - `ChefProfileView.swift`: View displaying the profile of a student chef.
  - `OrderView.swift`: View for placing orders for specific dishes.
  - `ReviewView.swift`: View for leaving and viewing reviews and ratings.
  - `OrderModel.swift`: Data model representing user orders.
  - `ChefModel.swift`: Data model representing student chefs and their information.
  - `MenuModel.swift`: Data model representing menus and menu items.
  - `NetworkingManager.swift`: Handles network requests to communicate with the backend.
  - `DataStore.swift`: Manages local data storage and retrieval.
  - ...

- `Assets`: Folder containing images, icons, and other graphical assets.
- `CuisineConnectTests`: Folder for unit tests related to the app's logic.
- `CuisineConnectUITests`: Folder for UI tests to ensure graphical interface functionality.
- `Preview Content`: Folder for data used in SwiftUI previews.
- `Preview Assets`: Folder for assets used in SwiftUI previews.

## Getting Started

### Prerequisites

- Xcode (Version 14.3.1)
- Swift (Version 5.8.1)

### Installation

1. Clone this repository to your local machine.
   
   ```bash
   git clone https://github.com/RobertFlemingii/CuisineConnect.git
   cd CuisineConnect
