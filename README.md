# Cafe Bliss

**Cafe Bliss** is a feature-rich and visually stunning Android application designed to enhance the way users browse and order coffee, sandwiches, and donuts. Built using Java in IntelliJ IDEA, this project exemplifies modern Android development practices, combining functionality with an intuitive design for a seamless user experience.

---

## What It Offers

Cafe Bliss serves as a digital menu and order management tool for cafes, bakeries, and small food businesses. With its elegant interface and robust functionality, it empowers both users and business owners by creating a streamlined ordering experience.

Key highlights include:
- **Menu Browsing**: Effortlessly explore various items like donuts, coffee, and sandwiches, each with customizable options.
- **Order Management**: Add, update, or remove items from your cart. You can even clear entire orders if needed.
- **Custom Quantities**: Easily select the desired quantity for any item before adding it to the cart.
- **Enhanced Usability**: The app ensures a delightful experience with visual feedback, responsive navigation, and interactive controls.

Whether you're running a cafe or looking to pickup/deliver, **Cafe Bliss** delivers a professional solution for your needs.

---

## Features

1. **Interactive Menu**: 
   - A beautifully organized interface lets users browse through categories like donuts, coffee, and sandwiches.
   - Each menu item is accompanied by relevant details, such as descriptions and pricing.

2. **Dynamic Order Management**:
   - Add multiple items to your order with a single tap.
   - Modify quantities or delete specific items directly from the cart.
   - Clear all orders effortlessly for a fresh start.

3. **Modern UI Components**:
   - **RecyclerView**: Dynamic and smooth scrolling through menu items.
   - **Alert Dialogs**: Confirm critical user actions like deleting an order.
   - **Spinners and Lists**: Intuitive selection for item customization.
   - **Toast Notifications**: Quick feedback for every user action.

4. **Multi-Screen Navigation**:
   - Navigate between different activities, including the main menu and order summary, for a seamless experience.

5. **Data Persistence**:
   - Utilizes the **Singleton Pattern** to manage and share data globally across activities, ensuring consistency.

6. **Localizable Text**:
   - All UI text is stored in the `strings.xml` resource file, making the app easy to translate and maintain.

7. **Custom Branding**:
   - Includes a unique launcher icon to give the app a professional and recognizable look.

---

## Tech Stack

- **Language**: Java
- **IDE**: IntelliJ IDEA / Android Studio
- **Platform**: Android
- **Design**: XML for layout and UI components
- **Data Handling**: Singleton Pattern for efficient global data management
- **User Interaction**: RecyclerView, Spinners, and Toast notifications for smooth user experience

---

## Getting Started

### Prerequisites
Before you begin, ensure you have the following tools installed:
- **Android Studio** (latest version recommended)
- **Java Development Kit (JDK)** 8 or higher
- **Android Virtual Device (AVD)** with API Level 28 or higher (optional for emulation)

### Installation Steps
1. **Clone the Repository**:
   Clone the project to your local machine using the following command:
   ```bash
   git clone https://github.com/Vivekman24/CafeBlissApp.git
2. **Open the Project**: Launch your IDE and open the project
3. **Sync Gradle Files**: Allow Gradle to download all dependencies
4. **Build the Project**: Rebuild the project to verify that all configurations are correct
5. **Run the App**: Deploy the app to a device or emulator and test the features 
