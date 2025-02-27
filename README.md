
## Project Overview
This project is a Java-based animal simulation that includes various animal classes implementing different behaviors. The application allows users to manipulate and display the attributes of animals like Tigers, Dolphins, and Penguins. 

## Features
- Serialization and deserialization of objects
- Menu-driven interface for interaction
- Implementation of various interfaces
- File handling for object persistence

## Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd <project-directory>
   ```
3. Compile the Java files:
   ```sh
   javac *.java
   ```
4. Run the application:
   ```sh
   java Main
   ```

## Classes & Interfaces
### `Animal.java`
- Abstract base class implementing `Eat` interface.
- Contains common attributes like `nameOfAnimal`, `weight`, `height`, and `age`.

### `Tiger.java`
- Implements `Walk` and `Serializable`.
- Attributes: `numberOfStripes`, `speed`, `soundLevel`.
- Overrides `toString()` to display deserialized content.

### `Dolphin.java`
- Implements `Swim` and `Serializable`.
- Attributes: `color`, `swimmingSpeed`.
- Overrides `toString()` to display deserialized content.

### `Penguin.java`
- Implements `Walk`, `Swim`, and `Serializable`.
- Attributes: `isSwimming`, `walkSpeed`, `swimSpeed`.
- Overrides `toString()` to display deserialized content.

### `Main.java`
- Provides a menu-based interface for interacting with animals.
- Implements file writing and reading for object persistence.

### Interfaces:
- `Eat`: Defines eating behaviors.
- `Swim`: Defines swimming behaviors.
- `Walk`: Defines walking behaviors.

## Usage
1. Choose an animal from the menu.
2. Set and display animal properties.
3. Save and load animal data to and from files.



