# Example for failing clojure-lsp in calva when lein project.clj in subfolder

This is a minimal repro repo for https://github.com/BetterThanTomorrow/calva/issues/1866.

To test if clojure-lsp is working, open `code/src/code/core.clj`, place cursor on `println`, open command palette (`CTRL/CMD + SHIFT + P`) and run comand `Go To Definition`.

1. With VS Code open folder `reporoot`: clojure-lsp does not work.
2. With VS Code open folder `reporoot/code`: clojure-lsp does work.
