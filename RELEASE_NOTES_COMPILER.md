### 0.6.6

* Support ResizeArray.FindAll: PR #412

### 0.6.5

* Support decimal (converted to JS number): PR #413
* Support recursive records: PR #417

### 0.6.4

* Fix #411: for .. downto

### 0.6.3

* Fix watch compilation on Windows

### 0.6.2

* Integer conversions (see #407)

### 0.6.1

* Multiple bug fixes
* Internal Fable AST additions
* [Rewrite plugins](https://fable-compiler.github.io/docs/plugins.html#Creating-rewriter-plugins)
* Use let/const when compiling value bindings to ES6
* Compile pattern matching with string or number literals as switch statements

### 0.5.11

* Fix #382 (partially): Exclude files in "node_modules" when calculating the base
  directory of referenced dlls.

### 0.5.10

* Fix #369: Extra blank lines when running postbuild script
* Fix #375: Add warning when replacements change semantics (printf, Async.Start...)
* Fix #377: Remove null args at the end of method/constructor calls also with macros

### 0.5.9

* Fix type testing with Erased Unions
* Erase assigments generated for tuple, record and union gets
* Fix #370: Add warning when using unions or records with Dictionary (as keys) or HashSet
* Internal cleanup

### 0.5.8

* Use chokidar to watch for file changes
* Fix calculation of relative paths with special characters (like "#")
