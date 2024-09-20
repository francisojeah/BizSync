# BizSync - Offline-First Business Management Suite for SMEs

## Overview
BizSync is a mobile application built to support small and medium-sized enterprises (SMEs) in managing their daily operations effectively. The app operates **offline-first**, ensuring users can manage inventory, track sales, and generate invoices even when there is no internet connection. Once online, the app automatically syncs all data to the cloud, providing a seamless experience.

## Key Features
- **Offline Inventory Management**: Add, edit, and track product or service inventories with real-time low-stock alerts.
- **Sales Tracking**: Record sales transactions and generate detailed reports on sales performance.
- **Invoicing**: Create, send, and manage invoices directly from the app.
- **AI Demand Forecasting**: Predict future demand based on historical sales data to improve stock management.
- **Offline-First Capability**: Perform all core tasks offline and sync the data to the cloud when back online.

## Technologies Used
- **Frontend**: Flutter
- **Backend**: Firebase (Real-time Database)
- **Local Storage**: SQLite for offline data persistence
- **AI**: Basic machine learning for demand forecasting
- **Version Control**: Git

## Team Members
- **Francis Okocha-Ojeah**
- **Adanna Ned-Onuoha**

## Getting Started

### Prerequisites
To run this project, you'll need:
- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Firebase account for backend services
- A code editor such as VS Code or Android Studio

### Installation

1. **Clone the repo**:
    ```bash
    git clone https://github.com/your-username/bizsync.git
    cd bizsync
    ```

2. **Install dependencies**:
    ```bash
    flutter pub get
    ```

3. **Set up Firebase**:
   - Add your Firebase credentials (GoogleService-Info.plist for iOS and google-services.json for Android).
   - Update the Firebase settings in `lib/firebase_options.dart`.

4. **Run the app**:
    ```bash
    flutter run
    ```

## Usage

### Inventory Management
- Add or update products and services in your inventory.
- Monitor stock levels and get alerts when items are running low.

### Sales Tracking
- Record daily sales, including product quantities and payment types.
- Generate reports to get insights into your sales performance over time.

### Invoicing
- Easily create professional invoices for clients.
- Track the status of invoices (sent, paid, pending).

### AI Demand Forecasting
- Leverage historical sales data to predict demand for certain products.
- Get proactive restocking recommendations.

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add your feature"
    ```
4. Push the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Create a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact
For any questions or suggestions, feel free to reach out at **your-email@example.com**.

