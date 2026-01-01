# GuessingGame


## A Guessing game implemented in Rust + Zig using these for educational purpose:

+ **generics**
+ **comptime**
+ **build options**


this is a simple guessing game inspired y the rust lang book with only 2 diffrence:

1. random number generated via zig that is hosted in this repo:

https://github.com/RezaBani/random_number_generator

your folder structure should be something like this:

..Parent Folder
....random_number_generator

in fact you can easily setup this:

`$ git clone --recurse-submodules https://github.com/RezaBani/guessing_game`

change directory to the game and run it with cargo:

`& cd guessing_game`

`$ cargo run`

Note: it will take some time to run for the first time since it's building it's dependency as well.

But source code is more beautiful than the game itself :)
