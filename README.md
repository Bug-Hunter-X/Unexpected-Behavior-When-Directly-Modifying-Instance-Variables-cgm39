# Unexpected Behavior When Directly Modifying Instance Variables in Ruby

This example demonstrates a potential issue in Ruby when directly manipulating instance variables using methods like `instance_variable_set` and `instance_variable_get`. While these methods offer flexibility, they can bypass encapsulation and lead to unexpected behavior if not used carefully.  This is especially problematic in larger projects, decreasing maintainability and increasing the chance of bugs.

The `bug.rb` file contains the code demonstrating this issue, while `bugSolution.rb` offers a better approach.