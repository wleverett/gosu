Dear contributor,

Please follow these style guidelines for C++ & Objective C code:

* Follow the C++ 2003 (TR1) standard.
  The `<Gosu/TR1.hpp>` header facilitates this.
* Use `JavaClassNames`, `javaVariables.javaMethods()`, `AND_JAVA_CONSTANTS`.
  For enums, follow the Delphi style: `enum AlphaMode { amDefault, amAdditive }`
* Don't worry too much about trailing spaces or Windows/UNIX newlines.
  But please ensure that your commit does not change lines or files that you haven't touched otherwise.
* Indent in multiples of four spaces (not tabs). Don't use formatting that will break when using a proportional font.
* Place `{` on its own line in C and C++, but on the same line *inside* Objective C methods.
  The opening brace `{` for an Objective C method should be on its own line, though.
* Align the pointer star to the left in C and C++ (`char* str`), but to the right in Objective C (`NSString *string`).
* You don't have to break up lines of code at all, Xcode and MSVC can do that by themselves.
  This makes it easier to read the same code on a big screen and on a laptop, even in a split-screen enviroment.
* Place spaces only around infix operators: `((-4 + 6) * --a[76])`
  Do not use spaces after function names: `f(foo, bar)`
  But put a space after flow control keywords: `return 5`, `if (cond)`, `switch (x)`.

Thanks. --Julian
