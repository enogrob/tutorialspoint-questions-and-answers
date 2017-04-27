**Quiz Learn Ruby - Variables, Strings, Numbers**

1. Assign the variable x to the value 5. x is called a variable and 5 is the value. x is called a variable because it can be reassigned to another value.
```ruby
x = 5
```

2. What is the datatype of "Matt"?
```ruby
"Matt"
```

3. Is x a string?
```ruby
x
```

4. What does this expression evaluate to?
```ruby
"YO" + "LO"
```

5. What does this expression evaluate to?
```ruby
"Cool".+("io")

#=> "Coolio"
```

> This is another way to concatenate Strings. The previous example actually uses syntactic sugar (a deviation from formal syntax to enhance code readability) and this example uses the strict syntax.

6. What does this expression evaluate to?
```ruby
"bob" + 42

```
> This raises an error because a number (Integer to be precise) cannot be concatenated with a String.

7. What does this expression evaluate to?
```ruby
a = "Bat"
b = "woman"
a + b

#=> "Batwoman"
```

> When variables are assigned to values, the variable can be used in place of the value.

8. What does this expression print?
```ruby
my_name = "50 Cent"
my_name = "Miley"
p my_name

#=> "Miley"
```

> The my_name variable was assigned to the value "50 Cent", but then it was reassigned to the value "Miley". Once the my_name variable is reassigned to "Miley", it loses all knowledge that it used to point to "50 Cent".


9. Get the first letter from the string "Jaydakiss".
```ruby
rapper = "Jaydakiss"

"Jaydakiss"[0]
# OR
rapper[0]
```

> Basically everything in computer science is 0-indexed, so the counting starts at zero, not at 1.

10. Get the first through 3rd elements from the "Jaydakiss" string.
```ruby
"Jaydakiss"[0..2]
```

11. Get the last element from the "Jaydakiss" string.
```ruby
"Jaydakiss"[-1]
```

12. Replace the "l" in the following string with "m":
```ruby
word = "lace"
word[0] = "m"
puts word

#=> "mace"
```

13. Assign the variable my_dawg to the value "DMX"
```ruby
my_dawg = "DMX"

```

14. What does the following expression evaluate to?
```ruby
"Dead Poet" = fav_bar
```

> This raises an error. When variables are assigned, the variable must be on the left, follow by an equal sign, followed by the value.

15. What does the following expression print?
```ruby
something = "cats"
crazy = something
puts crazy
```

> This will print "cats" because the variables something and crazy both point to the same value.

16. What does the following expression evaluate to?
```ruby
3 + 4

#=> 7
```

17. What does the following expression evaluate to?
``` ruby
4 * 7

#=> 28
```

18. What does the following expression evaluate to?
```ruby
2 ** 3

#=> 8
```

> ** is used for exponents and 2 ** 3 is 2 to the power 3 or 2 * 2 * 2.

19. What does the following expression evaluate to?
```ruby
8 / 2

#=> 4
```

20. What does the following expression evaluate to?
```ruby
3 / 2

# 1
```

> This outcome is not 1.5 because we are performing Integer division (division between two Integers) and Integers do not have any decimals. Division between two integers always results in an integer.

21. What does the following expression evaluate to?
```ruby
3.0 / 2.0

# 1.5
```

> This outcome is 1.5 because we are performing division on Floating point numbers that have decimals.
3.0 / 2 and 3 / 2.0 also return 1.5.

22. What does the following expression evaluate to?
```ruby
"i am not shouting".upcase()

# "I AM NOT SHOUTING"
```

> This shows that Ruby has nifty methods that are built in to the String class. The syntax for using the built in methods is the value, followed by dot, followed by the method name.

23. Convert every letter of "YoLo BrAh" to lowercase.
```ruby
nice = "YoLo BrAh"
nice.downcase()

# OR
"YoLo BrAh".downcase()
```

24. Concatenate the following strings:
```ruby
first = "Beautiful "
second = "face tattoo"
first + second

# OR
first.+(second)

# OR
first.concat(second)
```

> The `+()` and `concat()` methods do the same thing (they're not exactly the same, but very similar). Notice the similarity with the previous examples: there is a string, followed by a dot, followed by the method names with another string as an argument.
Integers have useful built-in methods too. Convert the number 5 to the string "5". `5.to_s` `to_s` stands for "to string"

25. What is the problem with the following code?
```ruby
my variable = "Mr. White"

```

> This will raise an error because variables cannot have spaces in them. Ruby convention is to combine multi-word variable names with an underscore.
```ruby
my_variable = "Mr. White"
```

26. Update the code, so it can run successfully:
```ruby
band = "Blink" + 182

# band = "Blink" + 182.to_s
```
