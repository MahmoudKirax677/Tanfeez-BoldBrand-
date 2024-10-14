# Tanfeez Service Platform

**Description**:  
**Tanfeez** is a service platform that connects **vendors** (companies) with **users** looking for various services. Vendors can showcase their services, submit bids for user requests, and manage their orders through the platform. The app facilitates efficient order management, bidding processes, and service delivery, acting as a streamlined marketplace for service providers and users alike.

**Technologies Used**:
- **Flutter**: Cross-platform mobile development for Android and iOS.
- **Cubit (State Management)**: Ensures efficient and scalable state management throughout the app.
- **API Integration**: For seamless interaction between vendors and users, including service requests, bids, and order management.
- **Firebase**: Used for push notifications to keep users and vendors informed about order updates, new bids, and promotions.

**Key Features**:
- **Service Showcase**: Vendors can create detailed profiles and showcase their services with descriptions, pricing, and availability.
- **Bidding System**: Vendors can submit bids for user requests, and users can review and select the best offer based on price, reviews, and vendor reputation.
- **Order Management**: Users can manage their orders, track their status, and communicate directly with vendors. Vendors can update the status of orders and track their fulfillment.
- **Push Notifications**: Both users and vendors receive real-time notifications about bid submissions, order updates, and other critical events in the app.
- **Responsive Design**: The app is optimized for a wide range of devices, ensuring a smooth experience for all users.

**Architecture**:
- The app follows a **Cubit** architecture for state management, providing a clear separation between the UI and the business logic, making the app maintainable and scalable.
- **Repository Pattern** is used to manage data interactions, including service listings, bids, and orders, ensuring clean and testable code.

**Order and Bidding System**:
- **For Users**:  
   Users can submit service requests and receive bids from vendors. They can compare offers based on price, reviews, and vendor profiles. Once an offer is accepted, users can manage the order directly within the app, track its progress, and communicate with the vendor if necessary.
   
- **For Vendors**:  
   Vendors can view available user requests, submit their bids, and manage their offers. They have access to tools for managing orders, updating statuses, and communicating with users directly.

**Notification System**:
- The app uses **Firebase Cloud Messaging (FCM)** to send push notifications to both vendors and users about bid submissions, order updates, and other interactions.

**App Links**:
- [Google Play Store - Tanfeez](https://play.google.com/store/apps/details?id=com.bold.tanfez.tanfez)
- [Apple App Store - Tanfeez](https://apps.apple.com/iq/app/tanfeez/id6450669942)

**Live Demo**:  
Due to confidentiality, the source code is not available. However, a live demo can be provided during a meeting using an emulator like **Android Studio** or **Xcode** for iOS. You may request access to a testing environment for further review.

