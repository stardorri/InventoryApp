# Inventory App (CS 360 Project)
- This is a mobile inventory management application developed in Android Studio. 
It allows users to create accounts, manage inventory items, and receive alerts when stock is low.

## Features
- User login and account creation
- Add, edit, and delete inventory items
- SQLite database integration
- Low inventory SMS alerts

## Reflection
CS 360 Portfolio Artifact Reflection 
Angel Silva
This project is a mobile inventory management application designed to help users track items and monitor stock levels. The main goal of the app was to provide a simple and efficient way for users to manage inventory while preventing shortages. The app addresses user needs such as organizing items, updating quantities, and receiving alerts when inventory is low, which is especially useful in environments where keeping track of supplies is important.

To support these user needs, the app includes several key screens and features. The login screen allows users to create an account and securely access the app. After logging in, users are taken to the inventory screen, where they can add, edit, and delete items. The interface uses a structured layout with clearly labeled input fields and buttons, making it easy to understand and navigate. A table format is used to display inventory items, which helps users quickly read and interact with their data. Additionally, a low-inventory alert system sends an SMS notification when an item falls below a certain threshold. These design choices kept the user in mind by focusing on clarity, simplicity, and efficiency, which contributed to a successful user-centered UI.

When coding the app, I followed a step-by-step development approach. I started with core functionality such as user authentication and database integration, then gradually added features like inventory management and SMS alerts. This incremental process made it easier to debug issues and understand how different components interacted. I also focused on separating responsibilities between activities and maintaining organized code. These strategies can be applied in future projects to improve efficiency, maintainability, and scalability.

To test the application, I ran the app in an emulator and tested each feature individually, including account creation, login, adding and updating items, and triggering low-inventory alerts. I also tested edge cases such as empty input fields and invalid data. This testing process is important because it ensures the app functions as expected and helps identify bugs early. Through testing, I was able to catch issues related to input validation and feature flow, which improved the overall reliability of the app.

During the development process, one challenge I faced was implementing the SMS notification feature while handling user permissions. I had to ensure that the app properly requested permission and handled both approval and denial cases without breaking functionality. Overcoming this required researching how Android permissions work and designing a fallback behavior, which helped me better understand real-world app constraints.

One area where I was particularly successful was integrating multiple features into a cohesive application. The combination of user authentication, database-driven inventory management, and real-time SMS alerts demonstrates my ability to build a functional and interactive mobile app. This project reflects my growing skills in mobile development and my ability to apply user-centered design principles in a practical way.
