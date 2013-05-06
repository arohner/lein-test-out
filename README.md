lein-test-out is a leiningen plugin that runs all your tests and outputs to a file in junit XML or TAP format.

Installation
============

Add [lein-test-out "0.3.0"] as a dev-dependency to your project.clj. 0.3.0 is only supported on lein 2. For lein 1 support, use v 0.2.0 or earlier.

Usage
=====

```
lein test-out
```

test-out optionally takes an output format, and a filename to write to:

```
lein test-out junit test-results.xml
```

Valid output formats are "junit" and "tap".


License
=======
EPL, the same as Clojure
