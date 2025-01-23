# Double Mutable References in Rust: A Potential Pitfall

This repository showcases a simple example demonstrating how double mutable references in Rust can lead to unexpected behavior. While the code compiles and works as intended, it highlights a situation where an unsuspecting programmer might inadvertently introduce subtle bugs.

The example focuses on how modifying a value through nested mutable references affects the original variable. This type of error can be difficult to track down in larger, more complex codebases.