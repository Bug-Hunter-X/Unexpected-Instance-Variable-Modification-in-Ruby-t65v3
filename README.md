# Unexpected Instance Variable Modification in Ruby

This repository demonstrates an uncommon bug in Ruby related to modifying instance variables using `instance_variable_get` and assignment.  Directly assigning a new value to the result of `instance_variable_get` does not modify the instance variable itself.  The `instance_variable_set` method should be used instead.