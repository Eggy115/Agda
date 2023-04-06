# Agda
Agda is a dependently typed programming language based on intuitionistic type theory. It is designed for reasoning about mathematical properties of programs and proving their correctness. Here's an example of a simple program in Agda:

```agda
module HelloWorld where

open import Data.String

main : IO ()
main = putStr "Hello, World!\n"
```

This program uses the `Data.String` module to output the text "Hello, World!" to the console using the `putStr` function. The `main` function is of type `IO ()`, indicating that it performs I/O operations and returns no meaningful value.

When this program is compiled and run, it will display the text "Hello, World!" on the screen.

Agda programs are typically saved with the "`.agda`" file extension. For example, the "Hello, World!" program I showed earlier would be saved in a file named "HelloWorld.agda".
