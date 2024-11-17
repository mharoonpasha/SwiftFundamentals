# Git Repository
### https://github.com/mharoonpasha/SwiftFundamentals

#  00 - About Swift

### 0.1 - Introduction

- Swift is a fantastic way to write software for phones, tablets, desktops, servers, or anything else that runs code.

- Swift defines away large classes of common programming errors by adopting modern programming patterns

    -- Variables are always initialized before use.
    -- Array indices are checked for out-of-bounds errors.
    -- Integers are checked for overflow.
    -- Optionals ensure that nil values are handled explicitly.
    -- Memory is managed automatically.
    -- Error handling allows controlled recovery from unexpected failures.

### 0.2 - Setup

- Xcode 16.1
- https://developer.apple.com

    -- Downloads
    -- Applications
    -- Xcode
    -- New Project - Other - Blank
    -- New File - Blank Playground
    -- Comments
        ** Single Line //
        ** Multiline - can be used for single line as well /* */

### 0.3 - Apple Developer Program

    -- USD 99 per anum
    -- Publish your apps to AppStore
    -- Get the latest betas
    -- TestFlight : Invite up to 10,000 external users to try out beta builds using just their email address or by sharing a public link
    
### 0.4 - Documentation

    -- https://developer.apple.com
    -- https://docs.swift.org
    
# 1 - Constants and Variables

- Data Types

    -- Int
    -- Double
    -- Float
    -- Bool
    -- String
    
- Associate a name such as `firstName` or `age` with a value
- Values of variables `var` can be changed
- Values of constants `let` cannot be changed
- Must be declared before used

```
var firstName = "John"
var lastName = "Doe"
let fullName = firstName + " " + lastName 
```

- Type Safety and Type Inference

    -- Swift is a type-safe language
    -- performs type checks when compiling your code and flags any mismatched types as errors.
    -- Type inference is particularly useful when you declare a constant or variable with an initial value
    
- Type Annotations

```
var age: Int 
```

- Naming Contants and Variables
 
    -- camelCase naming convention
    -- can contain almost any character, including Unicode characters
    
- Print command
- Semicolons

    -- Swift doesn't require semicolon (;) after each statement
    -- Semicolons are required if you want to write multiple separate statements on a single line
