Getting started 002
===

```
$ pulp run
$ pulp build -O --to output.js
$ bower install purescript-math --save
```

```
$ pulp psci
> 1 + 2
3

> import Main
> diagonal 5.0 12.0
13.0

> double x = x * 2
> double 10
20

> :type true
Boolean

> :type [1,2,3]
Array Int
```

```
$ bower install purescript-globals
$ pulp psci
> :browse Global
> import Global (encodeURIComponent)
> encodeURIComponent "http://localhost/path/to?query=string#flagments"
"http%3A%2F%2Flocalhost%2Fpath%2Fto%3Fquery%3Dstring%23flagments"
```
