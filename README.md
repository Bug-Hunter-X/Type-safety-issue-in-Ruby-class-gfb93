# Ruby Type Safety Bug

This repository demonstrates a subtle bug related to type safety in Ruby. The code defines a simple class `MyClass` that stores a value.  The issue arises from the lack of strong typing in Ruby; the `value` attribute can be assigned values of different types without explicit type checking. This can lead to unexpected behavior or runtime errors.

The `bug.rb` file shows the erroneous code. The `bugSolution.rb` file demonstrates a solution using type checking or alternative approaches to enforce type safety.