# Fibot

Fibot is a simple example of a CSML chatbot using CSML Native functions.

In this bot, we are using a recursive function to calculate fibonacci numbers!

```cpp
fn fibonacci(n):
  if (n < 2) return 1
  return fibonacci(n - 1) + fibonacci(n - 2)
```