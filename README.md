# Literate Ruby

A basic implementation of [Literate Programming](https://en.wikipedia.org/wiki/Literate_programming) in Ruby. Currently it only runs your code.

## How to use

    You can use indentation:

        def hello(name)
            "Hello, #{name}!"
        end

        puts hello("Daniël")

    or greater than sign:

    > def bye(name)
    >   "Bye, #{name}!"
    > end
    > puts bye("Daniël")

Then save the literate file and run it on the command line:

    ./literate-ruby demo.lrb
