# Chlorine

[![Build Status](https://api.travis-ci.org/chlorinejs/chlorine.png)](https://travis-ci.org/chlorinejs/chlorine)

Chlorine (formerly Clojurejs) is a naive implementation of a Clojure subset language to Javascript translator. Chlorine is an attempt to implement the predictable semantics in the generated Javascript. Some of its features are:

* Consistent scoping in ``let`` and ``loop/recur`` forms
* Macros with ``defmacro``
* Implicit ``return`` from all forms
* ``loop/recur`` translates to Javascript ``for`` loops
* ``case`` translates to Javascript ``switch/case``
* Translates Clojure vectors, strings, keywords, symbols and maps to Javascript equivalents
* File-based dependencies through ``load-file`` and ``load-file-macros``
* Clojure destructuring forms in functions and `let`

Chlorine is available under the Eclipse Public License - v 1.0.

For more information see the chlorine [wiki](https://github.com/chlorinejs/chlorine/wiki).
