# Ruby Bug: Unexpected Behavior from Directly Modifying Instance Variables

This repository demonstrates a common but subtle bug in Ruby related to directly modifying instance variables using `instance_variable_set`. This practice is generally discouraged in favor of using accessor methods (getters and setters).

The `bug.rb` file shows the problematic code.  The `bugSolution.rb` provides a more robust and maintainable solution.  Read the file comments for more details.