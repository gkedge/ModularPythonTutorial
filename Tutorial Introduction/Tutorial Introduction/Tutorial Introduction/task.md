Generally, modular programming is an effort to group code into 'logical'
blocks. 'Logical' is loosely defined many different ways, but grouping
code starts from just breaking down monolithic code that is difficult to
maintain or test. Modules grouped in a way that captures related
behavior improves code readability (grok'ing), maintenance and
testability. Modular code can additionally be packaged in ways that
allow them to be shared among projects both private and public.

This tutorial, as a foundation, introduces Python's modular programming
building blocks (modules, packages (including namespace packages) and
explains Python's runtime mechanics of ingesting (importing) those
building blocks. Based on that foundation, the tutorial offers a
reasoned (opinionated!) way to structure a Python project's modular
source and test code.

The 'reasoned' structure strives to achieve modularity goals, use sane
importation practices that avoid programmatic alteration of sys.path yet
allow for script execution (including test code) to discover modular
packages in cogently predictable ways.

This tutorial does NOT elaborate on what makes for a 'good', testable,
distributable package. After this tutorial on the modular building
blocks and how Python's importation mechanics work, you will have a much
better base to start your packaging rationalization.
