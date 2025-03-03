CS360 Inventory Application

This app was created to help users keep track of inventory by making it easy to add, update, and delete items while monitoring stock levels. One of the key features is SMS notifications, which alert users when an item is running low or has been removed from the inventory. The goal was to provide a simple and efficient way to manage inventory without the need for constant manual checks.

To keep the app user-friendly, I focused on a clean and intuitive design. The main inventory screen displays all items clearly, while the add/edit item screen makes updating information quick and easy. There is also an SMS settings screen where users can enable notifications for low stock or deleted items. Simplicity was the priority in the design, ensuring that users could navigate the app without any confusion. The layout and controls were designed with everyday use in mind, making it easy for anyone to manage their inventory.

During development, I structured the database using SQLite to store inventory details and used SharedPreferences to save user settings like the phone number for SMS alerts. Writing clean and modular code was a focus to make future updates and debugging easier. This project reinforced the importance of keeping the code structured and scalable, which will be helpful in future applications.

Testing played a major role in ensuring everything worked properly. I tested the app using both an emulator and a real device to confirm that database functions, button interactions, and SMS notifications behaved as expected. One of the biggest challenges was handling SMS permissions correctly. If a user denied permission, I needed to make sure the app still functioned normally. Setting up proper permission handling and fallback options helped solve this issue.

Looking at the full development process, integrating different parts of the app, from the database to notifications, took careful planning. One of the most rewarding parts of this project was successfully getting SMS notifications to work while ensuring the app remained smooth and responsive.

Moving forward, I plan to take what I learned and apply it to future mobile development projects. Whether building new apps or improving existing ones, I will focus on user experience, efficient database management, and handling permissions properly. If I decide to publish this app on the Google Play Store, I will refine it further and make sure it meets all requirements. This project has been a great learning experience, and I’m looking forward to applying these skills in future work.
