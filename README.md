# Homework 4: Advanced Structural Patterns – Singleton & Adapter

📝 Task Description
This project implements two key structural design patterns: Singleton and Adapter. The work is divided into two parts:

🔹 Part 1: Configuration Manager (Singleton)
The Singleton pattern ensures that only one instance of the configuration manager exists in the application.

🔧 Implemented Features:
✅ Created the ConfigurationManager class that loads a set of configuration parameters (e.g., maxPlayers, defaultLanguage, gameDifficulty).
✅ Added a method to retrieve configuration values by key.
✅ Used lazy initialization to create the instance only when needed.
✅ Implemented a method to print all configuration settings.

🟢 Expected Behavior:
🔹 Calling getConfig("maxPlayers") should return "100".
🔹 The print method should display all configuration settings.

🔹 Part 2: Chat Service Adapter (Adapter)
The Adapter pattern allows integration of the legacy chat system with the new application.

🔧 Implemented Features:
✅ Created the LegacyChatService class to simulate the old system.
✅ Defined the ChatService interface with the sendMessage method.
✅ Implemented ChatServiceAdapter to map calls from the new interface to the legacy chat service.

🟢 Expected Behavior:
🔹 Calling sendMessage("Hello world!") through the adapter should return:

yaml
Копировать
Редактировать
Legacy Chat: Hello world!  
