# Grading Rubric for Homework #14

## Evaluation Criteria

Your submission will be graded based on the following criteria:

### Correctness (40 points)
- The program compiles without errors and runs without throwing any exceptions.
- The program terminates gracefully when appropriate, without requiring forced shutdown.

### Synchronization (30 points)
- Proper use of the `synchronized` keyword to control access to shared resources.
- Correct implementation of `wait()` and `notify()` methods to handle thread communication.

### No Data Loss (20 points)
- All data produced by the producer is eventually consumed by the consumer.
- No data is overwritten in the buffer before being consumed.
- The consumer does not read the same data more than once.

### Efficiency (10 points)
- The solution does not use busy-waiting (active spinning) for synchronization purposes.
- Threads are not unnecessarily blocked or put to sleep beyond the requirements of synchronization.

## Total Points: 100

Please note that failure to compile or repeated crashes during execution will result in a significant loss of points. Ensure that your program has been thoroughly tested before submission.
