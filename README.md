## pre-commit

A framework for managing and maintaining multi-language pre-commit hooks.

For more information see: https://pre-commit.com/


In this fork, I've made a couple of quick changes to the default output:

* Passed hooks clear their line (unless printing to a log file, not a terminal) after they pass.

* Skipped hooks never print anything, except in verbose mode.

The effect is to hide all output after running except from failed hooks, unless `-v` / `--verbose` is passed.
