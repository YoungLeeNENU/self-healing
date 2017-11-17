## Usage

Check out the `core.clj` comment section for example.

```clojure
(healing/with-healing (report [1 2 3 4 5 "a" "b"]))
;=>"The average is 3"

(healing/with-healing (report []))
;=>"The average is 0"
```

Copyright © 2016 Carin Meier

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
