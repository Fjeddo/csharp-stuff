# What?
Expression body is a C# version 6-7.0 feature, available for methods/functions, (read-only) properties etc. Read about it here https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/statements-expressions-operators/expression-bodied-members.

# Why?
Since I'm a fan of the functional paradigm, I'm always striving to make the code I'm writing easy to read and understand. That is why expression-bodied members is very nice, it more or less forces the code to be abstracted and built up by really small pieces of funtionality. If a method or property contains many lines of code it is probably a great opportunity for one to refactor, to tear it apart and implement the same overall functionality, but this time striving to make all pieces expression-bodies members.

# How?
Have a look at the before and after classes in the csproj in this folder. I really like the after version much more, even though at a first glance it might feel a little over-engineered and refactored way to long.
