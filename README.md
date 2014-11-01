fantasy-build
=============

Fantasy build slash dependency system for my fantasy language.

What kind of things does a thing like this have to deal with?
-------------------------------------------------------------

Dependency management
- Within project
    - Flagging for rebuild on change, and cascading rebuilds
- External
    - Versions
        - Essentially, a SAT solver with extras
        - Version pinning
        - Cascading rebuilds on new versions
    - Artifacts
    - Managed source/binaries
    - Fetching
    - Paths/Sandboxes
    - Some idea of OCaml style functors

Build orchestration
- Provide ways to make transformers, sources, sinks, and wire these together
- Built in basic transformers, sources and sinks
- Sources and sinks interact with the Dependency Management part of the system


Is it any good?
---------------

At the moment, no. It doesn't really exist.
