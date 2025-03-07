# Homework 4: Advanced Structural Patterns – Singleton & Adapter

# Overview
In this project, we explored two essential Structural Design Patterns: Singleton and Adapter. These patterns play a crucial role in managing global state and seamlessly integrating legacy components into modern systems.

# Part 1: Global Configuration Manager (Singleton Pattern)
The Singleton pattern guarantees that only one instance of the configuration manager is maintained throughout the application.

# Implementation Details:
✔ Developed the ConfigurationManager class to handle key-value configuration settings (e.g., maxPlayers, defaultLanguage, gameDifficulty).
✔ Added a method to fetch configuration values by key.
✔ Applied lazy initialization to instantiate the manager only when required.
✔ Implemented a method to display all settings for debugging.

# Expected Behavior ✅:
🔹 Calling getConfig("maxPlayers") should return "100".
🔹 The print method should output all stored configuration settings.

# Part 2: Chat Service Adapter (Adapter Pattern)
The Adapter pattern bridges the gap between the legacy chat system and the modern application, ensuring seamless communication.

# Implementation Details:
✔ Created the LegacyChatService class to mimic the old chat system.
✔ Defined the ChatService interface with a sendMessage method.
✔ Developed the ChatServiceAdapter to translate calls from the new interface to the legacy service.

# Expected Behavior ✅:
🔹 Calling sendMessage("Hello world!") via the adapter should produce the output:
Legacy Chat: Hello world!

# Next Steps ➡️:
Click on the adapter to continue.

# General Requirements
✔ Documentation:
The code includes clear comments explaining the logic behind each implementation.

# ✔ Testing:
🔹 ConfigurationManager correctly retrieves and displays configuration values.
🔹 ChatServiceAdapter accurately translates messages between systems.

# ✔ Code Quality:
🔹 Adheres to Single Responsibility and Dependency Inversion principles.
🔹 Uses clear naming conventions and follows best practices for code organization.

# 🔧 Compilation & Execution Instructions:
1️⃣ Compile the Java files.
2️⃣ Run the demo classes to verify functionality:

ConfigManagerDemo (for Part 1)
ChatAdapterDemo (for Part 2)
