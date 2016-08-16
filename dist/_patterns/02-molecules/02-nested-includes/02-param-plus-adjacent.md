Includes `molecules-adjacent` using pattern parameters to override the value of `bar` (to **4**). Additionally, this pattern has an adjacent data file that provides values for `foo` (**4**) and `bar` (**99**).

* `foo`'s value should be taken from this pattern's adjacent data file.
* `bar` would normally also be taken from the adjacent data file, but gets overridden by the the pattern parameter.
* `baz` falls back to the value in `data.json` since neither the adjacent data nor the pattern params override it. Furthermore, the included pattern's (i.e. `molecules-adjacent`) own adjacent data is ignored.

The expected result is therefore: **4, 4, 1**