# Compiler Options

Many are visible here: https://github.com/clojure/clojurescript/blob/r2080/src/clj/cljs/closure.clj#L1041

## Closure Compiler Options

https://github.com/clojure/clojurescript/blob/r2080/src/clj/cljs/closure.clj#L85-L112

### `:optimizations`

https://developers.google.com/closure/compiler/docs/compilation_levels

`:none`

`:whitespace`

`:simple`

`:advanced`

### `:pretty-print`

### `:print-input-delimiter`

## Other Options

### `:ouput-to`

### `:output-dir`

### `:output-wrapper`

https://github.com/clojure/clojurescript/blob/r2080/src/clj/cljs/closure.clj#L965

### `:target`

`:nodejs` ...

### `:hashbang`

### `:optimize-constants`

https://groups.google.com/d/topic/clojurescript/bSFK6CEE3PE/discussion

### `:static-fns`

### `:warnings`

### `:source-map`

https://github.com/clojure/clojurescript/wiki/Source-maps

## Library Dependency Options

http://lukevanderhart.com/2011/09/30/using-javascript-and-clojurescript.html

https://github.com/clojure/clojurescript/blob/r2080/src/clj/cljs/closure.clj#L520

### `:libs`

### `:foreign-libs`

### `:ups-libs`

### `:ups-foreign-libs`

### `:externs`

### `:use-only-custom-externs`

Default externs should be excluded.

https://github.com/clojure/clojurescript/blob/r2080/src/clj/cljs/closure.clj#L163
