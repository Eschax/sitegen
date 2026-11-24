# sitegen

A faster drop-in for makefun-site 1.0.0: a static site generator whose `run(input)`
returns, for one site's input, exactly the output tree makefun-site 1.0.0's build
returns, byte for byte — and faster. Templates are compiled to functions once,
Markdown inline text is escaped in whole runs, and slugs are memoised.

Entry for the make.fun bounty site-generator-speed-01-run-20261122.
