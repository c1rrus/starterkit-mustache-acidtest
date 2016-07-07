Simply includes `molecules-param-plus-adjacent`. However, this pattern has an adjacent data file that provides a value for `baz` (**5**).

* The adjacent JSON of the included `molecules-param-plus-adjacent` pattern should be ignored, so `foo` falls back to the original value in `data.json` (**1**).
* The included `param-plus-adjacent` pattern has a "hard-coded" pattern param that I expect to be picked up, so `bar` should be **4**.
* This pattern has its own adjacent JSON file which should be picked up, so `baz` should be **5**.

The expected result is therefore: **1, 4, 5**