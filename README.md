# flutter_standard_template

A new Flutter reusable template project with Clean Architecture and BLoC pattern. This Flutter
project demonstrates a robust and scalable architecture based on Clean Architecture principles and
the BLoC (Business Logic Component) pattern. It aims to provide a clear separation of concerns,
testability, and maintainability for your Flutter applications.

## Project Structure

The project follows a layered architecture, dividing the codebase into three main layers:

- **Presentation Layer:** Contains UI components (widgets, screens), BLoC classes for managing UI
  state, and event handling.
- **Domain Layer:** Houses the business logic of the application, including use cases, entities, and
  repository interfaces.
- **Data Layer:** Responsible for data access, including repositories that interact with data
  sources (API, database, etc.) and data models.

## Key Features

1. **Clean Architecture:** Ensures a clear separation of concerns, making the codebase more modular
   and maintainable.
2. **BLoC Pattern:** Provides a predictable and testable way to manage UI state and handle user
   interactions.
3. **Dependency Injection:** Utilizes a dependency injection framework (e.g., get_it) to manage
   dependencies and improve testability.
4. **API Integration:** Demonstrates how to interact with external APIs to fetch and manipulate
   data.
5. **Local Storage:** Shows how to persist data locally using a database or other storage
   mechanisms.
6. **Unit and Widget Testing:** Includes comprehensive tests to ensure the correctness of the
   application logic and UI components.
7. **Build Flavors:** Supports building different versions of the app (e.g., dev, staging,
   production) with distinct configurations.

## Getting Started

1. **Clone the repository:
   ** `git clone https://github.com/ruhulmath08/flutter_standard_template.git`

2. **Install dependencies:** `flutter pub get`
3. **Configure Build Flavours:**
4. **Run the app:**