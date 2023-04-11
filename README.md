 Movies App
 Movies App is a mobile application built with the Flutter framework that allows users to browse and search for movies from a database called Movies db. The app follows clean architecture principles to ensure maintainability, scalability, and testability of the codebase.

Features
Browse popular movies
Search movies by title
View detailed information about each movie, including rating, release date, synopsis, and cast
Add movies to favorites list
Watch movie trailers
Read reviews from other users
Architecture
 Movies App is built using clean architecture principles, which separates the application into several layers with clear responsibilities. This approach ensures that each layer can be developed and tested independently, making the codebase more maintainable and scalable.

The application consists of the following layers:

Presentation layer: This layer contains the UI components, such as screens, widgets, and controllers. It communicates with the domain layer through a ViewModel, which provides data and state management for the UI components.

Domain layer: This layer contains the business logic of the application. It defines the use cases and entities that represent the application's data. It communicates with the data layer through interfaces to ensure loose coupling and testability.

Data layer: This layer provides the implementation for data sources, such as local database and remote API. It communicates with the domain layer through interfaces to ensure loose coupling and testability.

Advantages
Clean architecture principles ensure that the codebase is maintainable, scalable, and testable.
Separation of concerns allows for independent development and testing of each layer.
Loose coupling between layers makes it easy to swap out implementations without affecting other layers.
Clear separation of responsibilities makes it easier for developers to understand the codebase and make changes.
Use of Flutter framework makes it easier to develop and maintain the application across multiple platforms.
Libraries and Frameworks
 Movies App uses the following libraries and frameworks:

Flutter: The mobile app development framework used for the application.
Dio: A powerful HTTP client for Dart, used for API communication.
Flutter Bloc: A state management library for Flutter.
GetIt: A simple service locator for Flutter.
Hive: A lightweight and fast key-value database for Flutter.
Mockito: A mocking framework for Dart used for testing.
Requirements
Flutter SDK version 2.0 or later.
Dart SDK version 2.12 or later.
Installation
To install and run the application:

Clone or download the repository from GitHub.
Open the project in your favorite IDE.
Run the flutter packages get command in the terminal to install the required dependencies.
Build the project and run it on an emulator or physical device.
Contributing
Contributions to JetHub Movies App are welcome! If you find a bug or have a feature request, please open an issue on GitHub. If you would like to contribute code, please fork the repository and submit a pull request.
