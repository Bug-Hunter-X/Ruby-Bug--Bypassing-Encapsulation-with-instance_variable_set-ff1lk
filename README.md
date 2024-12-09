# Ruby Bug: Bypassing Encapsulation with instance_variable_set

This repository demonstrates a common, yet subtle, bug in Ruby: directly manipulating instance variables using `instance_variable_set` and `instance_variable_get`. This approach bypasses the class's accessor methods, potentially undermining encapsulation and leading to unexpected behavior and maintainability issues.

**Bug Description:**
Direct access to instance variables is generally discouraged for its negative impact on code structure, maintainability, and testability.

**Solution:**
The recommended approach is to leverage getter and setter methods (or attr_accessor) to manage instance variables and maintain encapsulation.
