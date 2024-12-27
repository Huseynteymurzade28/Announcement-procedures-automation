# Announcement Procedures Automation System 📢✨

A comprehensive JavaFX application designed to streamline the management of organizational announcements, offering modern features and a user-friendly interface.

## Key Features 🌟

### User Authentication 🔒
- Secure login and registration functionalities.

### Diverse Announcement Types
- **Advertisements**: 📣 Promote events or products.
- **Proclamations**: 🗞️ Share official organizational updates.
- **Personal Announcements**: ✉️ For individual use or small groups.

### CRUD Operations ✏️
- Easily create, read, update, and delete announcements.

### Visual Categorization 🎨
- Intuitive grouping and display of announcements.

### Modern UI
- 🎨 Gradient backgrounds for a polished look.
- 📱 Responsive design to ensure usability across different screen sizes.

## Technical Stack 🛠️

- **Programming Language**: Java ☕
- **UI Framework**: JavaFX 🎭
- **Layout Design**: FXML 🖌️
- **Data Handling**: Google Gson and Jackson Annotations 📊
- **Build Tool**: Maven 🏗️

## Project Structure 🗂️

```plaintext
src/
├── main/
│   ├── java/
│   │   └── com/example/announcement_procedures_automation_projectoop/
│   │       ├── Controllers/        # Handles user interactions and application logic
│   │       ├── Announcements/      # Defines announcement types and logic
│   │       ├── CustomCells/        # Custom UI components for enhanced visuals
│   │       ├── DataBases/          # Simulated or actual database logic
│   │       └── Main.java           # Application entry point
│   └── resources/
│       └── com/example/announcement_procedures_automation_projectoop/
│           ├── Images/             # Assets for the UI
│           └── FXML files          # Layout files for JavaFX
```
# Setup Instructions 🛠️
## 1. Clone the Repository
```
git clone https://github.com/your-username/announcement-system.git
```
## 2. Install Java JDK
Ensure you have Java JDK 17 or later installed.
## 3. Install Maven
If not already installed, download and configure Maven.
## Gson
```
<dependencies>
    <dependency>
        <groupId>org.openjfx</groupId>
        <artifactId>javafx-controls</artifactId>
        <version>17.0.2</version>
    </dependency>
    <dependency>
        <groupId>com.google.code.gson</groupId>
        <artifactId>gson</artifactId>
        <version>2.10.1</version>
    </dependency>
    <dependency>
        <groupId>com.fasterxml.jackson.core</groupId>
        <artifactId>jackson-annotations</artifactId>
        <version>2.15.2</version>
    </dependency>
</dependencies>
```
## 4. Build the Project
```
mvn clean install
```
## 5. Run the Application
```
mvn javafx:run
```
# Dependencies 📦
#### JavaFX: For building the user interface.
#### Google Gson: To parse and handle JSON data.
#### Jackson Annotations: For data binding and serialization.
