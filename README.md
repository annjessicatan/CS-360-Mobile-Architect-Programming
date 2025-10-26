# CS-360-Mobile-Architect-Programming

## Portforlio Journal Reflection

The Inventory Management App I developed addresses critical needs for warehouse staff by providing a streamlined digital solution for real-time stock monitoring and management. This application was designed to replace inefficient paper-based systems with an intuitive mobile interface that enables quick stock checks, instant quantity updates and automated low-stock alerts. The primary user needs included rapid access to inventory data, simple item management without complex navigation and proactive notifications when supplies run low, all of which directly support warehouse efficiency and accuracy in daily operations.

To create a user-centered UI, I implemented three essential screens: a secure login system for data protection, a main inventory grid displaying all items with clear quantity information and an add/edit form for managing stock levels. The design prioritized large touch targets and intuitive visual hierarchy based on Android Material Design principles, ensuring warehouse staff could quickly complete tasks even in fast-paced environments. The interface successfully balanced simplicity with functionality by grouping related actions, maintaining consistent navigation patterns and providing immediate visual feedback for all user interactions, which made the app accessible to users with varying technical experience.

My coding approach followed a modular, incremental strategy that broke the development process into manageable phases. I began with database architecture and user authentication, then progressed to inventory CRUD operations and finally implemented the SMS notification system. This method allowed me to validate each component thoroughly before integration and made debugging more systematic. The technique of building core functionality first and then adding features progressively is a strategy I can apply to future projects to maintain momentum and ensure stable foundation layers before addressing more complex requirements.

I employed continuous testing throughout development using Android Studio's emulator, conducting functionality checks after implementing each major feature. This process revealed the importance of testing permission handling scenarios early, as I discovered the emulator automatically denies SMS permissions for security reasons. Rather than indicating a failure, this actually demonstrated that my error handling worked correctly, the app gracefully degraded by maintaining full functionality while clearly communicating the disabled notification status to users. This testing approach highlighted how robust applications must perform reliably under various system conditions and user choices.

During the full development process, I innovated in designing the database helper class to efficiently manage both user authentication and inventory operations within a single SQLite database. This required creating a flexible architecture that could scale from initial user setup to handling complex inventory transactions while maintaining data integrity. The challenge of ensuring persistent data storage across app sessions was overcome by implementing proper database lifecycle management and transaction handling, which provided a reliable foundation for all other application features.

I was particularly successful in demonstrating my knowledge and skills through the comprehensive RecyclerView implementation for the inventory grid display. This component showcased my understanding of Android architecture components, efficient data handling with Cursor adapters and responsive UI design. The inventory grid not only displayed items effectively but also integrated seamless delete functionality, automatic data refresh and smooth scrolling performance. This complex component brought together multiple development concepts into a cohesive user experience that directly addressed the core requirement of providing warehouse staff with immediate, reliable access to inventory information.


## Inventory App's Key Features
![alt text](https://github.com/annjessicatan/CS-360-Mobile-Architect-Programming/blob/main/CS-360%20Inventory%20App%20Images/icon.png "Inventory App Icon")<br>
Inventory App's icon<br>

![alt text](https://github.com/annjessicatan/CS-360-Mobile-Architect-Programming/blob/main/CS-360%20Inventory%20App%20Images/SMS%20Dialog.png "SMS Permission Dialog")<br>
SMS Permission Dialog<br>

![alt text](https://github.com/annjessicatan/CS-360-Mobile-Architect-Programming/blob/main/CS-360%20Inventory%20App%20Images/Main%20Inventory%20Grid.png "Main Inventory Grid")<br>
Main Inventory grid with sample items

