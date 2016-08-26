# Programming Language Classifier

Create a classifier that can take snippets of code and guesses the programming language of the code.

### Languages to classify
- C (.gcc, .c)
- C#
- Common Lisp (.sbcl)
- Clojure
- Haskell
- Java
- JavaScript
- OCaml
- Perl
- PHP (.hack, .php)
- Python
- Ruby (.jruby, .yarv)
- Scala
- Scheme (.racket)

### Steps:

1. Getting a corpus of programming languages

2. Write a classifier function that takes a string of code and returns a guess for the language the code was written in.
3. Test your classifier
      - polyglot folder contains the test files (test.csv contains a list of the file names in the test directory and the language of each snippet)
