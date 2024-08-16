This is a collection of annotations on the 1997 Definition of Standard
ML. It presents the definition as a series of enumerated clauses, with
comments and annotations.

Running the makefile will produce a PDF output (as well as a DVI
output). This requires `dvipdfmx`. If you'd prefer to use `pdflatex`,
then you'll need to change the Makefile.

-----

This is not a "rational reconstruction" of the Definition using
contemporary programming language theory, TAPL-like techniques, theorem
provers, or anything fancy. It is just an attempt to digest the
Definition and provide more explanations about what's going on.

If I had to teach the Standard ML Definition, then I would probably not
use these annotations. Instead what you should do is work through a
large collection of example code snippets, show how static semantics
_elaborate_ and dynamic semantics _evaluate_ each example. The
difficulty with such an approach is picking the examples, and ordering
them.

Perhaps that would be best left as a collaborative effort. "SML
Definition by Example".