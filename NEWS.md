
## development version 

### new

* `trim` has a new argument `value` that allows trimming rows and columns with other values than the default `NA`
* `rapp` has a new argument `clamp` that allows clamping start and end values to 1-nlyr(x), avoiding that all values are considered `NA`

### bugs fixed

* `extract` did not work for horizontal or vertical lines as their extent was considered invalid (bug reported by Monika Tomaszewska)
* autocor did not handle NA values [#192](https://github.com/rspatial/terra/issues/192)
