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

### `:preamble`

### `:closure-defines`

### `:closure-warnings`

### `:ouput-to`

### `:output-dir`

### `:output-wrapper`

https://github.com/clojure/clojurescript/blob/r2080/src/clj/cljs/closure.clj#L965

### `:static-fns`

> It's an option mostly because of REPL development to allow for redefinition. For example if :static-fns true we statically dispatch to specific fn arities - but what if you redef to a different set of arities? What if you change the var to store a deftype instance that implements IFn. That kind of thing.

> So for compilation :static-fns can nearly always be true, but for the REPL it's not desirable.

– https://groups.google.com/d/msg/clojurescript/holhVap5Rjc/f9bUE26waakJ

Implied by `:optimizations :advanced`

`cljs.analyzer/*cljs-static-fns*`

### `:warnings`

### `:source-map`

https://github.com/clojure/clojurescript/wiki/Source-maps

### `:optimize-constants`

Implied by `:optimizations :advanced`

Generates `constants_table.js` in the output directory.

https://groups.google.com/d/topic/clojurescript/bSFK6CEE3PE/discussion

## node.js

### `:target`

`:nodejs`

Includes `cljs/nodejs.cljs` and `cljs/nodejscli.cljs`, and adds a hashbang.

### `:hashbang`

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
