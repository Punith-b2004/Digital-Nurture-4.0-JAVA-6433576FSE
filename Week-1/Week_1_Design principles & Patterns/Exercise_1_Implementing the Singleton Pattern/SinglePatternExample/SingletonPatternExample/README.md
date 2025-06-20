# Singleton Pattern Example

This project demonstrates the implementation of the Singleton design pattern in Java through a logging utility class.

## Purpose of the Singleton Pattern

The Singleton pattern ensures that a class has only one instance and provides a global point of access to that instance. This is particularly useful for logging utilities, where having a single instance can help maintain consistent logging throughout the application lifecycle.

## Logger Class

The `Logger` class is designed to follow the Singleton pattern. It contains:

- A private static instance of itself to hold the single instance.
- A private constructor to prevent instantiation from outside the class.
- A public static method `getInstance()` that returns the single instance of the `Logger`.

## Usage

To use the `Logger` class, simply call `Logger.getInstance()` to obtain the single instance and use it for logging messages.

## Testing

The `LoggerTest` class is provided to verify the Singleton implementation. It checks that only one instance of the `Logger` class is created and used throughout the application.

## Conclusion

This project serves as a practical example of the Singleton design pattern in Java, showcasing how to implement and test a logging utility that adheres to this pattern.