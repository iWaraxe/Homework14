# Homework #14: Producer-Consumer Synchronization

## Objective
Implement thread synchronization in a producer-consumer scenario to gain hands-on experience with concurrency and multi-threading concepts in Java.

## Task Description

In this homework assignment, you will address a classic concurrency problem known as the producer-consumer scenario. You are required to implement the following components:

1. **Buffer Class**: A storage class that holds integers. This buffer should have a maximum size limit.
2. **Producer Class**: A class that implements `Runnable` and simulates data production by placing an integer into the buffer every second.
3. **Consumer Class**: A class that also implements `Runnable` and simulates data consumption by taking an integer from the buffer every second.

The primary challenge is ensuring that the producer does not add data to a full buffer, and the consumer does not attempt to consume data from an empty buffer.

## Requirements

- **Thread Synchronization**: Use the `synchronized` keyword, `wait()`, and `notify()` methods to handle synchronization between the producer and consumer threads.
- **Buffer Management**: Implement logic within the Buffer class to handle full or empty states.

## Code Skeleton

```java
class Buffer {
    // Implement the necessary properties and methods here.
}

class Producer implements Runnable {
    private Buffer buffer;

    // Constructor and run method.
}

class Consumer implements Runnable {
    private Buffer buffer;

    // Constructor and run method.
}

public class Main {
    public static void main(String[] args) {
        // Initialize Buffer, Producer, and Consumer, and start the threads.
    }
}
```