CS 360 Module Eight Journal Reflection
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The goal of my application was to create a mobile inventory management system that allows users to keep track of inventory items in a simple and organized way. The application allows users to create an account and log in, view inventory information, add new inventory items, update quantities, delete items, and receive SMS notifications when inventory reaches a low level. The app was designed to help users keep track of their inventory without needing to manually maintain a separate inventory list.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The main screens included the login screen, inventory screen, SMS notification settings screen, and the sensor demonstration screen. The inventory screen was designed to display items clearly while providing buttons for increasing, decreasing, and deleting inventory. The application also includes navigation buttons so users can move between the inventory and SMS notification screens. I kept users in mind by making the controls straightforward and using clear labels. The design was successful because users can understand what each feature does without needing complicated instructions.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached the coding process by building the application in smaller sections and testing each section before moving forward. I used Java for the application logic and SQLite for persistent data storage. I created a database helper to manage users and inventory data and used separate activities for different application functions. I also used comments and consistent naming conventions to make the code easier to understand. This approach can be applied to future projects because breaking a larger application into smaller components makes it easier to identify and correct problems.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the application using the Android Emulator and repeatedly closed and restarted the application to make sure the information and functionality continued to work. I tested logging in, navigating between screens, adding inventory items, changing quantities, deleting items, and accessing SMS notification settings. I also tested the application while developing the SensorManager functionality. Testing was important because it revealed problems that were not always obvious when looking at the code. Fixing these problems helped ensure that the final application could launch and function correctly.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One challenge was connecting the different parts of the application while keeping the navigation functional. I had to troubleshoot issues involving activities, layouts, themes, and database functionality. I also had to make sure the SMS permission process would not prevent the rest of the application from working if the user denied permission. Working through these problems required testing different solutions and using the Android Studio tools to identify errors. This experience showed me that development often requires adapting the original design when technical challenges occur.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful with the inventory management functionality and database integration. The application can store inventory information in a SQLite database and provides the basic CRUD operations needed for an inventory system. I also successfully implemented login functionality and SMS permission handling. These components demonstrated my ability to connect the user interface, application logic, and database into a functional mobile application.
