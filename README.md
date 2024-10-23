# CS360-Mobile_Architecture - Android Inventory Management App

## Project Overview

This Android application is an inventory management system designed to help users track and manage their inventory items efficiently. The app addresses the need for a mobile-friendly solution to monitor stock levels, update quantities, and receive timely notifications for low inventory.

### Key Features

- User Authentication: Secure login and account creation
- Inventory Management: Create, read, update, and delete inventory items
- Database Integration: SQLite database for persistent data storage
- SMS Notifications: Optional alerts for low inventory levels
- User-friendly Interface: Grid display of inventory items

## User-Centered Design

The app's UI was designed with the end-user in mind, focusing on simplicity and functionality. Key screens include:

1. Login/Registration Screen
2. Main Inventory Grid View
3. Item Detail/Edit Screen
4. Add New Item Screen
5. Settings Screen (for SMS permissions)

The grid layout for inventory display ensures easy scanning and management of items, while intuitive icons and buttons facilitate quick actions like adding or editing items.

## Development Approach

### Coding Strategies

- Modular Development: Breaking down the app into distinct components (authentication, database operations, SMS functionality)
- Version Control: Utilizing Git for code management and tracking changes
- Agile Methodology: Iterative development with frequent testing and refinement

These strategies can be applied to future projects to maintain code organization, facilitate collaboration, and ensure continuous improvement.

### Testing Methodology

- Android Emulator: Extensive use for testing various device configurations and Android versions
- Unit Testing: For individual components like database operations and authentication logic
- User Permission Testing: Ensuring app functionality with and without SMS permissions
- Edge Case Testing: Verifying app behavior with empty inventories, large datasets, and network issues

Rigorous testing was crucial to identify and fix bugs, ensure smooth user experience across different scenarios, and validate the app's reliability.

## Challenges and Innovations

One significant challenge was implementing a flexible notification system that respects user permissions. The solution involved creating a fallback notification method within the app when SMS permissions were denied, ensuring users still received important alerts about their inventory.

## Successful Component Highlight

The SQLite database integration stands out as a particularly successful component. It demonstrates proficiency in:

- Efficient data modeling for inventory management
- CRUD operations implementation
- Data persistence across app sessions
- Optimized queries for smooth performance, even with large inventories

This component showcases the ability to design and implement a robust backend system crucial for the app's core functionality.

## Conclusion

This inventory management app successfully meets the project requirements while providing a user-friendly solution for small business owners or individuals needing to track their inventory. The combination of secure authentication, efficient data management, and optional SMS notifications creates a versatile tool adaptable to various user needs.
