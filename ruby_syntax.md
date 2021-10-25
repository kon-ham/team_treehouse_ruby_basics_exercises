- Which of these is NOT a valid method call?

    `puts[1, 2, 3]`

- If you want to run a program named "total.rb" in the current directory, what would you type in the terminal?

    `ruby total.rb`

- If you're currently in a directory that contains a "code" directory, and the "code" directory contains a file named "add.rb", which of these options would run "add.rb"?

    ```
    cd code
    ruby add.rb
    ```

- What's the conventional file name extension for Ruby source code files?

    `.rb`

- What is a method?

    `A method of code statements that work together to do some kind of useful work`

- In this Ruby program, make a call to the puts method. Pass puts the string "Hello, world!" as an argument.

    `puts("Hello World!")` or `puts "Hello World!"`

- Define a method named say_hi. The method body should include a call to puts with an argument of "hi". Then call your new say_hi method.

    ```
    def say_hi
        puts "hi"
    end

    say_hi
    ```

- Assign the string "Ruby" to a variable named language. Then assign the string "awesome" to a variable named description. Then make a single call to puts and pass it two arguments: the language and description variables. (Remember that if you're providing multiple arguments for a method call, you separate them with commas.)

    ```
    language = "Ruby"
    description = "awesome"

    puts language, description
    ```

- Define a method named say. The say method should take one parameter (name the parameter whatever you want). In the say method body, take the parameter and pass it to puts as an argument. End your program with a call to the say method, and pass the string "Ruby" as an argument.

    ```
    def say(parameter)
        puts parameter
    end

    say("Ruby")
    ```

- Define a method named three that always returns the number 3. Also define a method named five that always returns the number 5. Neither method should take any arguments. (We know, these methods aren't especially useful. We just want to see if you know how to make a method return a particular value!)

    ```
    def three
        return 3
    end

    def five
        return 5
    end
    ```

- Which of these is a valid Ruby variable name, that also follows variable naming conventions?

    `user_name`

