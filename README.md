panic because i spaced out
==========================
A silly little reproducer to show that backtraces for panics completely break if there are spaces in the path leading up to the package. As long as there is some part of the path with a space, it breaks. It does not need to be the project itself, though I have done so to make it easy to reproduce.
